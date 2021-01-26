# SMT-sudoku-solver
Fast sudoku SAT-solver in Satisfiability Module Theories (SMT) for Z3

Given sudoku field of 81 variables from a11..a99:

a11|a12|a13|a14|a15|a16|a17|a18|a19
a21|a22|a23|a24|a25|a26|a27|a28|a29
...
a91|a92|a93|a94|a95|a96|a97|a98|a99

- Starting sequence already implemented with 7 random numbers. -> change for different sudoku

Implemented on QF_LIA in Z3 (either use Z3 online or download and use with terminal)
Also possible on Yices, CVC4 or integration with Boolector.

