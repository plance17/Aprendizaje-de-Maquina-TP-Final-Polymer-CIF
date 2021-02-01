The polymer datase includes 1073 CIF files, each of them provides the optimized structure and the accompanied properties calculated with first-principles computations with VASP. The standard inputs used for this dataset are given in terms of an INCAR file as below

PREC       =  Accurate
ENCUT      =  400
EDIFF      =  1.d-4
ISMEAR     =  0
SIGMA      =  0.01
EDIFFG     = -1.0E-02
IBRION     =  2
ISIF       =  3
# vdw-DF2
GGA        =  ML
LUSE_VDW   = .TRUE.
Zab_vdW    = -1.8867
AGGAC      =  0.0000

Five structures, including 0001.cif, 0010.cif, 0012.cif, 0015.cif, and 0027.cif have been relaxed with EDIFFG = -1.0E-03, meaning that the atomic forces have to be smaller than 0.001 eV/Angstrom.

