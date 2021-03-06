Architecture - GPU Vs CPU
=========================
###GPU
A graphics processing unit (GPU), also occasionally called visual processing unit (VPU), is a specialized electronic circuit designed to rapidly manipulate and alter memory to accelerate the creation of images in a frame buffer intended for output to a display. GPUs are used in embedded systems, mobile phones, personal computers, workstations, and game consoles. Modern GPUs are very efficient at manipulating computer graphics and image processing, and their highly parallel structure makes them more effective than general-purpose CPUs for algorithms where processing of large blocks of data is done in parallel.

###CPU
A central processing unit (CPU) is the electronic circuitry within a computer that carries out the instructions of a computer program by performing the basic arithmetic, logical, control and input/output (I/O) operations specified by the instructions. The term has been used in the computer industry at least since the early 1960s.Traditionally, the term "CPU" refers to a processor and its control unit (CU), distinguishing these core elements of a computer from external components such as main memory and peripherals

The form, design and implementation of CPUs have changed over the course of their history, but their fundamental operation remains almost unchanged. Principal components of a CPU include the arithmetic logic unit (ALU) that performs arithmetic and logic operations, hardware registers that supply operands to the ALU and store the results, and the control unit that fetches instructions from the main memory, and decodes and executes them while relying on the ALU and registers as necessary to perform decomposed operations.

###GPU ACCELERATED COMPUTING
GPU-accelerated computing offers unprecedented application performance by offloading compute-intensive portions of the application to the GPU, while the remainder of the code still runs on the CPU. From a user's perspective, applications simply run significantly faster. 

![ctgi](https://github.com/dineshappavoo/ctgi/blob/master/src/com/ctgi/images/how-gpu-acceleration-works.png "GPU Acceleration")

###CPU VERSUS GPU
A simple way to understand the difference between a CPU and GPU is to compare how they process tasks. A CPU consists of a few cores optimized for sequential serial processing while a GPU has a massively parallel architecture consisting of thousands of smaller, more efficient cores designed for handling multiple tasks simultaneously.
 
GPUs have thousands of cores to process parallel workloads efficiently


![ctgi](https://github.com/dineshappavoo/ctgi/blob/master/src/com/ctgi/images/cpu-and-gpu.jpg "GPU Vs CPU")

###Video Clip from NVIDIA

<a href="http://www.youtube.com/watch?feature=player_embedded&v=-P28LKWTzrI
" target="_blank"><img src="http://img.youtube.com/vi/-P28LKWTzrI/0.jpg" 
alt="http://img.youtube.com/vi/-P28LKWTzrI/15.jpg" width="540" height="380" border="10" /></a>


Graphics processors (GPUs) provide a vast number of simple, data-parallel, deeply multithreaded cores and very high memory bandwidths as illustrated by Figure 1. GPU architectures are becoming increasingly programmable, offering the potential for dramatic speedups for a variety of general purpose applications compared to contemporary general-purpose processors (CPUs).

![ctgi](https://github.com/dineshappavoo/ctgi/blob/master/src/com/ctgi/images/gputech_perf_chart.png "GPU Vs CPU flops chart ")

The reason behind the discrepancy in floating-point capability between the CPU and the GPU is that the GPU is specialized for compute-intensive, highly parallel computation � exactly what graphics rendering is about � and therefore designed such that about 80% of transistors are devoted to data processing rather than data caching and flow control Because the same function is executed on each element of data with high arithmetic intensity as schematically illustrated by Figure 2

![ctgi](https://github.com/dineshappavoo/ctgi/blob/master/src/com/ctgi/images/gputech_f2.png "GPU Vs CPU arch")

While GPU has many benefits such as more computing power, larger memory bandwidth, and low power consumption regarding the high computing ability, there are some constraints to fully utilize its processing power. These constraints make performance optimization more difficult and also its debugging environment is not as powerful as in general CPU. Therefore, developing a code with GPU can takes more time and need more sophisticated work. In addition, GPU code runs in parallel so that data partition and synchronization technique are needed. In some cases of algorithm, there are often no algorithms which can be fit into GPU so that a new parallel algorithm for GPU needs to be developed. 

###Referrences

* [nvidia.com](http://www.nvidia.com/object/what-is-gpu-computing.html)
* [wikipedia.org](http://en.wikipedia.org/wiki/Graphics_processing_unit)
* [allegroviva.com](http://allegroviva.com/gpu-computing/difference-between-gpu-and-cpu/)

