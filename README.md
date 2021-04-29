# OpenMP-Monte-Carlo-Simulation

Link: http://web.engr.oregonstate.edu/~mjb/cs575/Projects/proj01.html

Introduction
Monte Carlo simulation is used to determine the range of outcomes for a series of parameters, each of which has a probability distribution showing how likely each option is to happen. In this project, you will take a scenario and develop a Monte Carlo simulation of it, determining how likely a particular output is to happen.

Clearly, this is very parallelizable -- it is the same computation being run on many permutations of the input parameters. You will run this with OpenMP, testing it on different numbers of threads (1, 2, and 4, but more are OK).
