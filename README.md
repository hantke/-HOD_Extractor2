HHH   HHH    OOOOOOO    DDDDDDD
HHH   HHH   OOOOOOOOO   DD    DDD
HHHHHHHHH   OOO   OOO   DD    DDD
HHHHHHHHH   OOO   OOO   DD    DDD
HHH   HHH   OOOOOOOOO   DD    DDD
HHH   HHH    OOOOOOO    DDDDDDDD

EXTRACTOR v2.00

The assembly bias evolution. Contreras et al. 2018
_______________________________________________________________________________________________

        HOD_Extractor/HOD.hdf5 include all HOD measured for Guo et al. 2013.

This include:

- 7 redshift bins (z= 0, 0.5, 1, 1.5, 2, 2.5, 3)
- 6 number densities (n/h^3Mpc^-3 = 0.0316, 0.01,0.00316, 0.001, 0.000316, 0.0001)
- Based in 2 galaxy properties (Mstell & SFR)

The HODs are measured for bins of 10% of the age and concentration of the haloes,
for a total of ~1800 HODs.

All masses are in logarithm and in units of Msun/h 

       Fit_Extractor/Fit.hdf5

For the galaxies selected by stellar mass, we are realizing the HOD parameters
and their error using the parametrisation introduced by Zheng et al. 2005. 
The error is calculated as the square root of the diagonal of the covariance matrix.

In addition, we are presenting 2 extractor and plotting tools per file (a python and a python notebook code)

_______________________________________________________________________________________________

We recommend deepdish to extract the HDF5 files 
http://deepdish.readthedocs.io/en/latest/

For an alternative way to extract these HODs is also available at:
https://github.com/hantke/HOD_Extractor

Any doubt or concern please do not hesitate in contacting me at stcontre@uc.cl


