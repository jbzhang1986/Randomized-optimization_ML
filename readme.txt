This project implement four local random search algorithms. They are:

randomized hill climbing
simulated annealing
a genetic algorithm
MIMIC
use the first three algorithms to find good weights for a neural network.
The file cwang493.analysis.pdf contain:
results I obtained running the algorithms on the networks
a description of my optimization problems
analyses of my results


Instructions for running the code:
.m files are run in MATLAB
The ABAGAIL package is run through a JAVA developing program, such at NetBeans


Code for the Neural Network problem (cancer cells):
execute random\solveNN.m


Codes for the Rastrigin function:
execute random\solveRas.m
MIMIC algorithm: ABAGAIL\src\opt\test\RasTest.java


Codes for the TSP :
execute random\solveTSP.m
MIMIC algorithm: ABAGAIL\src\opt\test\TravelingSalesmanTest.java


Codes for One-Max problem:
ABAGAIL\src\opt\test\CountOnesTest.java
