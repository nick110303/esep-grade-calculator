# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

What Each File Does:
i) README.MD  - ReadMe File used to tell the user how to utilize the program
ii) mod.go - defines the module name, Go version, and dependencies for the project
iii) grade_calculator.go - main source file for the project, and defines the logic for defining grades
iv) grade_calculator_test.go - contains unit tests for the functions in grade_calculator.go
