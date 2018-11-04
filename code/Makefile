EXECS=mpi_hello_world
MPICC?=mpicc

all: ${EXECS}

mpi_hello_world: mpi_hello_world.c
	${MPICC} -o mpi_hello_world mpi_hello_world.c

mpi_isend_irecv: isend_irecv.c
    ${MPICC} -o isend_irecv isend_irecv.c

clean:
	rm -f ${EXECS}
