CMU 15418 Assignment 1: Analyzing Program Performance on a Multi-Core CPU
=========================================================================

Please refer to the [course website](http://15418.courses.cs.cmu.edu/spring2016/article/3) for instructions.

# Build on Windows
The assignment starter code can be compiled on both Windows and Linux. Following instructions are specific for running on Windows.
==Platform Requirement
You need Visual Studio 2017 to compile the starter code on Windows. 
You can download Visual Studio 2017 Community here: https://www.visualstudio.com/thank-you-downloading-visual-studio/?sku=Community&rel=15
## Preparation
You will need Intel ISPC compiler for this assignment. 
1. Download ISPC at http://sourceforge.net/projects/ispcmirror/files/v1.9.1/ispc-v1.9.1-windows-vs2015.zip/download
2. Extract ispc.exe into assignment1\ispc\ directory.
## Run
With ispc.exe at correct location, you can compile and run the assignment using assignment1.sln
## Changing the command line argument to ISPC
If you wish to explore different ISPC command line arguments when compiling an ispc file (e.g. prog3_mandelbrot_ispc\mandelbrot.ispc), you may do so directly in Visual Studio.

1. Right click the ispc source file in Solution Explorer, and select Properties.

![alt text](https://github.com/tsinghua-15418/assignment1/raw/master/readme_figures/fig1.jpg "")

2. Ensure "Configurations" and "Platform" are both set to "Active", and change the text in the "Command Line" row.
![alt text](https://github.com/tsinghua-15418/assignment1/raw/master/readme_figures/fig2.jpg "")

Note that you'll need the "--arch=x86" argument if you are building 32bit applications (Win32 platform), and the "--arch=x86-64" when building 64bit applications (x64).

# Build on Linux
Instructions for building on Linux is included in the [course website](http://15418.courses.cs.cmu.edu/spring2016/article/3).
