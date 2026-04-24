# Go Calculator

A simple calculator application built with Go that performs basic arithmetic operations.

## Features

- ✅ Addition
- ✅ Subtraction
- ✅ Multiplication
- ✅ Division (with zero-division error handling)

## Installation

Clone the repository:
```bash
git clone https://github.com/qiukuip/go-calculator.git
cd go-calculator
```

## Usage

Run the calculator:
```bash
go run calculator.go main.go
```

## Example

The calculator includes example operations:
- Addition: 10 + 5 = 15
- Subtraction: 10 - 5 = 5
- Multiplication: 10 * 5 = 50
- Division: 10 / 5 = 2

## Functions

- `Add(a, b float64) float64` - Returns the sum of two numbers
- `Subtract(a, b float64) float64` - Returns the difference of two numbers
- `Multiply(a, b float64) float64` - Returns the product of two numbers
- `Divide(a, b float64) (float64, error)` - Returns the quotient with error handling for division by zero

## License

MIT License