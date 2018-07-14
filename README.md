Nonlinear Control of Quadrotors
===============================

[![nbviewer](https://cdn.rawgit.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/) [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/plusk01/nonlinearquad/master)


This repo hosts a collection of Jupyter/IPython notebooks that implement various control schemes for quadrotors.

## Table of Contents ##

| Notebook                  | Topics                                                                                   |
|---------------------------|------------------------------------------------------------------------------------------|
| [quadrotor_model][1]      | introductory material, derivation of equations of motion, base `Quadrotor` class         |
| [quadsim][2]              | the simulation framework that handles all of the plumbing from different components      |
| [utils][3]                | a set of utilities useful to multiple notebooks                                          |
| [pid][4]                  | a simple successive-loop PID controller to verify that the simulation is working         |
| [smc_cranfield][5]        | an introductory example of sliding mode control for the inner loop by Shaik \[1]         |
| [sliding_mode_control][6] | a more in-depth sliding mode control scheme by L'Afflitto \[2]                           |

[1]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/quadrotor_model.ipynb
[2]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/quadsim.ipynb
[3]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/utils.ipynb
[4]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/pid.ipynb
[5]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/smc_cranfield.ipynb
[6]: http://nbviewer.jupyter.org/github/plusk01/nonlinearquad/blob/master/sliding_mode_control.ipynb

## References ##

\[1] M. K. Shaik and J. F. Whidborne, “Robust Sliding Mode Control of a Quadrotor,” 11th Int. Conf. Control, pp. 1–5, 2016.

\[2] A. L’Afflitto, R. Anderson, and K. Mohammadi, “An Introduction to Nonlinear Robust Control for Unmanned Quadrotor Aircraft,” IEEE Control Syst. Mag., vol. 38, no. June, pp. 102–121, 2018.
