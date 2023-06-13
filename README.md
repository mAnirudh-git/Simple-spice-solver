# Simple-spice-solver
This project contains all the codes and brief explanation including simultaneous equation solver, intelligent user input interface, what is in the .netlist file and the solver of simplified circuits.

The .ipynb file contains:
1. Equation solver of any number of variables, but with equal no. of linear equations (both real and complex coefficients) to solve. Gives solutions if they exist. Gaussian method is used.
2. It has code to take correct inputs of coefficients of equations. The intelligent part in it is that it keeps repeatedly asking the same coefficient until user inputs the correct type.
3. Contains code that can read an entered '.netlist' file and outputs data in such a form that any one can easily understand the circuit.
4. The final code can solve a circuit that is input as '.netlist' file and output all the nodal voltages and auxiliary currents for both ac and dc sourced cats.
*Note: Circuits should be in their simplest forms example if there 2 resistors in parallel, put it as a single equivalent resistance.
