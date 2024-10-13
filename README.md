# Parallel-Matrix-Chain-Multiplication





## Description

This program finds the most efficient way to multiply a chain of matrices using MPI to distribute the computation. It determines the optimal parenthesization that minimizes the number of scalar multiplications.

## Requirements

- **Language**: C/C++ (recommended), Python
- **Framework**: MPI

## Input Format

- The first line contains an integer `N` (number of matrices).
- The second line contains `N + 1` integers representing the dimensions of the matrices.

## Output Format

- Print one integer representing the minimum number of scalar multiplications.

## Example

### Input
```
4
40 20 30 10 30
```

### Output
```
26000
```

## How to Run

1. Compile the program:
   ```bash
   mpicc -o matrix_chain 5.cpp
   ```

2. Run the program with MPI:
   ```bash
   mpiexec -np <number_of_processes> ./matrix_chain <input_file>
   ```

---
