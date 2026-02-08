# Python Calculator

This repository contains a simple Python calculator project that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Files in this Repository

- `calculator.py`  
  A Python module that defines functions for basic arithmetic operations:
  - add
  - subtract
  - multiply
  - divide (with error handling for division by zero)

- `main.ipynb`  
  A Jupyter Notebook used to test and demonstrate the calculator functions interactively.

## Features

- Clean and simple function-based design
- Error handling for division by zero
- Easy to extend with more operations

## How to Use

### Using the Python file
Import the calculator module in your Python script:

```python
from calculator import add, subtract, multiply, divide

print(add(2, 3))
print(divide(10, 2))
