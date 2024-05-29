# raman-sc
It was revised from raman-sc: https://github.com/raman-sc/VASP

For more information please visit: https://github.com/raman-sc/VASP/tree/master

When use the old python code with VASP >= 5.4.4, it gives error:

[get_modes_from_OUTCAR]: ERROR Couldn't find 'Eigenvectors after division by SQRT(mass)' in OUTCAR. Use 'NWRITE=3' in INCAR. Exiting..

I revised the lines to search for the frequence informations in the OUTCAR, So it can be used in VASP 6.4.2.
