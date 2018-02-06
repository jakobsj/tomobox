# tomobox
A few tools for tomographic reconstruction experiments

Tiny collection of tools that enables simple experiments with tomographic reconstruction of three-dimensional objects from two-dimensional projections using a parallel beam geometry.

# The zip-file contains the following files:

buildSystemMatrix.m: Sets up a tomographic system matrix for a parallel beam geometry in three dimensions

getNoise.m: Creates a vector of Gaussian white noise.

phantom3d.m: Create a three-dimensional extension of the classic Shepp-Logan test image. This file is made by Matthias Schabel and published at the MATLAB File Exchange as File ID: #9416, https://uk.mathworks.com/matlabcentral/fileexchange/9416-3d-shepp-logan-phantom

plotLayers.m: Displays the layers of threedimensional array.

tomoboxDemo1.m: Demo script to run a simulation including generating a test image, choosing random projection directions, computing projections, adding noise, and finally reconstructing by use of the iterative linear solver LSQR.

traceRays.m: Aux. function for buildSystemMatrix.