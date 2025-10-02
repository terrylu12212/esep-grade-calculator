# ESEP Grade Calculator

Description

This library is a simple utility to calculate your grades.

Functionality

grade_calculator.go - functions for converting a numerical grade to a letter grade, adding grades, calculating the average grade, and calculating a numerical grade based on the weighted average of the assignment types and their respective averages.

grade_calculator_test.go - functions to test if given inputs that should yield a letter grade of 'A', 'B', and 'F' are correctly calculated. If the functionality and actual value calculated within grade_calculator.go is different from the expected value, then an error is thrown.

Runtime requirements:
Golang 1.24+


Installation:
Clone the repository: https://github.com/terrylu12212/esep-grade-calculator.git

Ensure that Golang is installed and up-to-date with the Runtime requirements

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```
