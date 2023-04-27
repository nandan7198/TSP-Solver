# Travelling Salesman Problem Solver
 This project is a Java implementation of the Travelling Salesman Problem solver, which uses the Nearest Neighbor and 2-OPT algorithms. The aim of this project is to find the shortest possible path that visits each node in a given graph exactly once and returns to the starting node.

## Algorithms
<h3>Nearest Neighbor</h3>
The Nearest Neighbor algorithm is a simple greedy algorithm that starts at a random node and repeatedly selects the nearest unvisited node until all nodes have been visited. This algorithm does not guarantee the optimal solution, but it is often used as a starting point for more sophisticated algorithms.

<h3>2-OPT</h3>
The 2-OPT algorithm is an iterative improvement algorithm that attempts to improve an existing solution by iteratively swapping pairs of edges to create a shorter path. This algorithm can be used in combination with the Nearest Neighbor algorithm to further improve the solution.
 
 ### Note
Please change the input file name(fileName variable) in the Main.java file before executing it.
