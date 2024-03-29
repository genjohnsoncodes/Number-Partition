# Number Partition Using a GA

The Number Partitioning Problem (NPP) is an NP-hard problem which a set of positive integers must be partitioned into two sums where the sums are equal, or as close to equal as possible. There are multiple ways to find an optimal solution. This repo contains an Genetic Algorithm capable of producing more than one optimal solution.

To use the GA run the number part file with a file containing the numbers to be partitioned, an example:
.\number_part.py ..\data\data10.dat

A user can change the mutation rate, elitism, and population size with -m, -e, -p respectively followed by the number that they wish to change them to.

This project was created for a Evolutionary Computation class at St. Cloud State University in collaborations with Ben Jacobs.