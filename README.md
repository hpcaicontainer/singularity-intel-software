# Singularity Container for Intel Software
Singularity container for Intel Parallel Studio XE Runtime, Intel MPI, Intel MKL, etc.

[**Intel® Parallel Studio XE Runtime**](https://software.intel.com/content/www/us/en/develop/articles/installing-intel-parallel-studio-xe-runtime-2020-using-yum-repository.html) includes everything you need to run applications built with **Intel® Parallel Studio XE**. The runtime doesn't include the compiling tools, such as mpicc, etc.

**[Intel MPI and Intel MKL](https://software.intel.com/content/www/us/en/develop/articles/installing-intel-free-libs-and-python-yum-repo.html)** is free to use for personal and commercial purpose now.



### Usage

```
[root@localhost build]# singularity build psxe.simg intel-psxe-runtim.sif
[root@localhost build]# singularity shell psxe.simg
Singularity psxe.simg:/> mpirun --help

Usage: ./mpiexec [global opts] [local opts for exec1] [exec1] [exec1 args] : [local opts for exec2] [exec2] [exec2 args] : ...

Global options (passed to all executables):

```

