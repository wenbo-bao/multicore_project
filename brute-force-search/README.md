
# nqueens_stop.c compute [solution_count] count of solutions
# how to run nqueens_stop.c

1. setup environment

module load gcc-12.2
export OMP_CANCELLATION=true

2. compile
gcc -O -fopenmp -o nqueens_stop nqueens_stop.c

3. 

./nqueen_bfs [problem_size] [thread_count] [solution_count]

# nqueens_stop.c compute [solution_count] count of solutions
# how to run nqueens_all.c

1. setup environment

module load gcc-12.2

2. compile
gcc -O -fopenmp -o nqueens_all nqueens_all.c

3. 

./nqueens_all [problem_size] [thread_count]