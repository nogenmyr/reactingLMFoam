# reactingLMFoam
Basically reactingFoam 2.3.x, but with a low Mach number assumption

Add thermodynamic pressure level in constant/chemistryProperties

pReff pReff [1 -1 -2 0 0 0 0] 1.01325E+05;

Further, you will need a new field-file: pd (dynamic pressure), which
is actually your solved pressure variable (p is more or less a dummy field)
