kde
---
Multi-dimenstional Kernel Density Estimation (KDE) including adaptive
bandwidths and C and CUDA implementations for specific cases.


Authors
-------
Sebastian Schoenen (schoenen@physik.rwth-aachen.de) and Martin Leuermann for
the IceCube collaboration.


Installation Instructions
-------------------------
Download the software into directory <DIR>. There should be a subdirectory
named "kde" within the <DIR> directory.

To install in a location independent of your system Python files, install via
the following command:

$ pip install <DIR>[cuda] --user

where [cuda] is optional, ensuring support for GPU.

To install with references to the source code where it is downloaded (so that
changes in the sourcecode are reflected immediately):

$ pip install -e <DIR>[cuda] --user

For windows installation install all required software with pip or conda and run
following in the kde-directory while in your prefered python environment

$ pip install ".[cuda]"


