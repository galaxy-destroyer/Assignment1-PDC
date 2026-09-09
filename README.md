# Assignment1-PDC
MPI
Link: https://github.com/galaxy-destroyer/Assignment1-PDC/

To run part1a:
COMPILE: mpicc -o part1a part1a.c -lm
COMPILE WITH DEBUG PRINTF: mpicc -o part1a part1a.c -lm -DDEBUG
RUN: mpirun -n <num_process> ./part1a <num_particles> <num_timesteps> <size_timesteps> <output_frequency> <g|i>

eg. of running cmd: mpirun -n 4 ./part1a 8 100 0.01 10 g


To run part1b: 
COMPILE:

RUN: 