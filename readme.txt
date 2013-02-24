Peter J. Lu
23 Feb 2012
http://www.peterlu.org
plu@fas.harvard.edu
Copyright 2013 Peter J. Lu

This document provides instructions on how to test the particle-location code, including the programs:

plu_centerfind2D
plu_link3dt
plu_struct3dt

**If you use this code, please cite in your publications:
Peter J. Lu, Peter A. Sims, Hidekazu Oki, James B. Macarthur, and David A. Weitz, 
"Target-locking acquisition with real-time confocal (TARC) microscopy,"
Optics Express Vol. 15, pp. 8702-8712 (2007).

Information on the details of the algorithm are given in Chapter 6 of: 
Peter J. Lu, "Gelation and Phase Separation of Attractive Colloids,"
Harvard University PhD Thesis (2008).

This directory contains the built executables for Ubuntu 64-bit linux, and several 3D stacks of particle data. 

1. Copy the executable from the /release directories of the Eclipse projects for all code. This should replace the existing executables, which you want to test.

2. Execute the script:

./phi41pct_130210.sh

This will launch a combination of all of the programs, and will create an output file from the 3D radial distribution function g(r).
 

This is a preliminary draft of these instructions. If things are unclear or do not function as described, please contact me so we can resolve the issues.
