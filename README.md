# Celestial Log-Soft Current OPE Calculations

This Mathematica code package performs symbolic calculations for the Operator Product Expansion (OPE) of celestial log-soft currents involving spherical harmonics and differential operators. The code is modular, facilitating symbolic expansions, series calculations, and simplified results for specific integer-based celestial operations.

## Purpose

The primary goal of this code is to calculate and simplify OPEs in celestial amplitudes, particularly focusing on expressions involving R operators with symbolic variables and assumptions. This code handles series expansions, differentiation, and limiting processes necessary for these calculations.

## Installation

1. Install Mathematica (version 12 or later recommended).
2. Clone this repository or download the `.nb` (notebook) file.
3. Open the notebook in Mathematica to start working with the code.

## Usage

The code is designed to be modular and adaptable. The main functions include:
- `computeOPE[l, k, a]`: Computes the full OPE for specified parameters, expanding each term and applying limits.
- `computeTreeOPE[l, k, λ]`: Computes the tree-level OPE with handling for symbolic and series expansions.
  
Each function takes symbolic arguments that represent parameters in the celestial OPE calculations:
- `l`, `k`: Positive integers used in defining the indices of the R operators.
- `a`, `λ`: Parameters controlling specific aspects of the OPE and series expansion.

**Example Usage**:
```mathematica
(* Compute the full OPE *)
computeOPE[2, 3, 0.5]

(* Compute the tree-level OPE *)
computeTreeOPE[2, 3, 1]
