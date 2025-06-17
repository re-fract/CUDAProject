# CUDAProject
FInal Project for "CUDA at Scale for the Enterprise"

# Project Description
This application generates a single PNG image showing an input grayscale image alongside its progressively downscaled versions. Given a value k (1–9) and an N x M image, it outputs a (3/2)N x M image containing the original and its downscales by factors of 2 up to 2^k.

Example input and output are in data/sloth.png and data/sloth-gray.png. Run it using run.sh.

# Code Organization

```bin/``` This folder holds all binary/executable code that is built automatically or manually.

```data/``` This folder holds all example data in any format.

```src/``` The source code for this project.

```README.md``` The description of the project so that anyone cloning or deciding if they want to clone this repository can understand its purpose to help with their decision.

```Makefile``` Script for building this project's code
