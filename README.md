# Euler-_Solver_-OpenMP-
Solver for integral-differential equations for first and second spatial moment using Euler method.\
These programs carries out experiments 14.4 and 14.6 (LawDieckmann200a.pdf: pages 13, 17)
\
\
_Tested on Ubuntu 22.04 and SteamOS._
\
\
HOW TO COMPILE THE PROGRAMS:

1. Before compiling, navigate to the main body of Solver.cpp and uncomment the experiment of your choice.
2. Launch command promt from the folder containing the programs.
3. Input the following lines:
```
g++ Solver.cpp -fopenmp -O3
```
```
./a.out
```
