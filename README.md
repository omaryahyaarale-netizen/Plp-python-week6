# PLP Python Week 6 Assignment

## Overview
This project contains solutions for the PLP Week 6 assignment on Python exception handling using `try` and `except`.

## File Included
- `safe_tools.py`

## Functions

### 1. safe_divide(a, b)
Safely divides two numbers.
- Returns the result of `a / b`
- Returns `"Cannot divide by zero"` if division by zero is attempted

### 2. safe_number(text)
Converts text into an integer.
- Returns the integer value if conversion is successful
- Returns `"Not a number"` if conversion fails

### 3. get_field(learner, key)
Retrieves a value from a dictionary.
- Returns the value associated with the given key
- Returns `"Field not found"` if the key does not exist

## Sample Output

```text
5.0
Cannot divide by zero
42
Not a number
82
Field not found