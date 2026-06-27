# Test Cases

## Test Case 1 – Complete Information

**Result:** All fields extracted successfully into valid JSON.

## Test Case 2 – Missing Phone Number

**Expected:** `"phone": null`

## Test Case 3 – Missing Email Address

**Expected:** `"email": null`

## Test Case 4 – Missing Purchase Date

**Expected:** `"purchase_date": null`

## Test Case 5 – Missing Multiple Fields

**Expected:** Missing fields should be returned as `null` while available information should be extracted correctly.

## Validation

* Delimiters (`"""`) used.
* Few-shot prompting implemented.
* Output restricted to valid JSON.
* No conversational text generated.
* Missing values handled using `null`.
