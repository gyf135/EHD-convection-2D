# EHD-convection-2D
The code is written in C++ with CUDA GPU computing to solve the 2D electrohydrodynamics convection under unipolar discharge

Windows with Visual Studio:

Project properties => C/C++ Additional Include Directories:

1. Need to add: C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v9.2\bin for cufft 

File properties => General => Excluded From Build for LBM.cu, poisson.cu

2. Need to compile main.cu, LBM.h, seconds.cpp, seconds.h only

For Linux:
Please use the command in the compile.sh file
