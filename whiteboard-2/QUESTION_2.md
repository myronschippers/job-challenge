# DNA Verify & Clean

Write a function that takes in an array that should contain DNA base values and returns a string with any non-canonical bases removed. Canonical base values are 'C', 'T', 'A', and 'G'.

**Clarifications (only if asked):**

You can assume the array will only contain strings
The canonical DNA bases are fixed single character values that will not change
Case insensitive - 'a' should be treated the same as 'A', but return only capitals
If the array is empty, return an empty string

**Example test cases:**

- `[ 'A', 'H', 'T', 'C' ] -> 'ATC'`
- `[ 'hmC', 'T', 'G', 'A', 'aC' ] -> 'TGA'`
- `[ 'a', 'G', 't', 'c' ] -> 'AGTC'`
- `[ ] -> ''`