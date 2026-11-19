# 2-Loop Circuit Numerical Solver (Gauss-Seidel Method)

This repository contains a computational physics project implementing the Gauss-Seidel iterative method to solve Kirchhoff's voltage laws for a 2-loop electrical circuit.

## Technical Parameters
- Resistors: $R_1 = 15\,\Omega$, $R_2 = 25\,\Omega$, $R_3 = 40\,\Omega$
- Voltages: $\varepsilon_1 = 18\,\text{V}$, $\varepsilon_2 = 10\,\text{V}$
- Convergence Tolerance: $10^{-8}$

## Features
- Matrix formulation of linear equations ($A\mathbf{x} = \mathbf{b}$)
- Iterative computation with residual analysis and error tracking
- Multi-panel visualization (Current convergence vs. Iterations and Log-residual drop)

## Technologies Used
- Python (`numpy`, `pandas`, `matplotlib`)
- Google Colab# gauss-seidel-circuit-solver
Python implementation of Gauss-Seidel method for solving 2-loop electrical circuits.
