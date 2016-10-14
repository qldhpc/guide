# An Introduction to High Performance Computing \(HPC\)

High Performance Computing most generally refers to the practice of aggregating computing power in a way that delivers much higher performance than one could get out of a typical desktop computer or workstation in order to solve large problems in science, engineering, or business.

A High Performance Computing Cluster is a collection of individual machines joined together so that the individual nodes can work together to solve a problem larger than any one computer can easily solve. The cluster typically has a number of different elements; there are compute nodes to run programs, a fast file system to allow the storage and quick access of large amounts of data, control nodes to coordinate, and a fast network to join everything together.

Most HPC machine typically run a Linux Operating System and do not have a graphical user interface. Instead access to the machine is provided by a command line interface, which can be used from anywhere in the world.

## Lyra

Our University's HPC cluster is called Lyra (named after the constellation Lyra), and was manufactured by Silicon Graphics International Corp. (SGI). Originally installed in 2007 it has gone though many upgrades and currently contains approximately 4400 CPU cores.

The current configuration is:
* 218 nodes with 4368 Intel cores
  *  1 node with 32 E7-8837 CPUs, 1024GB RAM
  * 16 nodes with 16 E5-2670 CPUs, 256GB RAM
  * 60 nodes with 16 E5-2670 CPUs, 128GB RAM
  * 16 nodes with 16 E5-2670 CPUs, 64GB RAM
  * 30 nodes with 20 E5-2680v2 CPUs, 128GB RAM
  * 16 nodes with 20 E5-2680v2 CPUs, 256GB RAM
  *  1 nodes with 24 E5-2680v3 CPUs, 128GB RAM
  * 80 nodes with 24 E5-2680v3 CPUs, 256GB RAM
* GPUs
  * 8 M2090 Nvidia GPUs (2 per node)
  * 12 K40 Nvidia GPUs (2 per node)
  * 4 K80 Nvidia GPUs (4 per node)
* 8 Intel Xeon Phi co-processors.

The disk system consists of:
* 2 PB of DMF backed up disk
* 2 PB of Lustre (parallel disk) also backed up by DMF.
* A dual site tape library.

The network is a mix of QDR and FDR InfiniBand



