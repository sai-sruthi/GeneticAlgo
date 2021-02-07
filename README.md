# Travelling Salesman Problem using GeneticAlgo

Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city?"
It is an NP-hard problem in combinatorial optimisation. The worst-case running time for any algorithm for the TSP increases super polynomially with the number of cities.
For example, we take 3 cities then there are 3 x 2 x 1 different routes( i.e 3! ) to pick in total but if now take 10 it becomes 3628800 and 20 it is gigantic 2432902008176640000.
if we want to find the shortest route for our map of 20 locations we would have to evaluate 2432902008176640000 different routes! Even with modern computing power, this is terribly impractical, and for even bigger problems, it's close to impossible so I have tried to reduce the computations using Genetic Algorithm.
See project Travelling Salesman Problem using Genetic Algorithm
