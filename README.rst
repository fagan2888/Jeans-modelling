Jeans-modelling
=====

**A python script to perform MCMC dynamical modelling of galaxies using the spherical Jeans equations with constant orbital anisotropy**. 

The method is described in `Mamon & Lokas (2005) <http://adsabs.harvard.edu/abs/2005MNRAS.363..705M>`_.

In order to use this script you need :

- the `emcee <https://github.com/dfm/emcee>`_ python module to run the MCMC machinery 
- the file phot.py, which defines some useful functions to be used in jeans.py

In order to run the script:

1) open jeans.py

2) input the text-file containing the velocity dispersion data you want to fit

3) edit the photometric quantities of your tracer

4) the script returns a text-file that you can rename at the bottom of the script

5) run the script with : python jeans.py
