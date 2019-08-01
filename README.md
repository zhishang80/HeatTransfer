# Heat
Finite difference method for 2D heat transfer. Fortran90 with MPI-2 parallel I/O and MPI-3 neighbourhood collectives
make and ./run
or
mkdir build && cd build
cmake ..
make 
mpirun -np 8 heat
