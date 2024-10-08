# Dbar_method_for_EIT
This repository is for sharing code for the so-called D-bar method for Electrical Impedance Tomography. The mathematics behind the method is explained in the book Linear and nonlinear inverse problems with practical applications by Jennifer L Mueller and Samuli Siltanen (SIAM 2012). 

Electrical Impedance Tomography (EIT) aims to recover the internal electrical conductivity of a physical body from measurements of voltages and currents at the boundary of the body. EIT has applications in medical imaging, underground prospecting, and nondestructive testing. The image reconstruction problem of EIT is a nonlinear and severely ill-posed inverse problem. The D-bar method is a non-iterative regularized reconstruction method based on low-pass filtering a nonlinear Fourier transform. This repository contains Matlab routines implementing the D-bar method for simulated EIT data.

Software: Matlab, including PDE toolbox (probably works also with Octave).
The codes were designed and written by Jennifer Mueller, Samuli Siltanen and Janne Tamminen.
