This file keeps track of major changes applied to the code after the first 
release (version 1.0.0)

10/03/2017
==========

1. Added module "atmosphere.py" including methods for relevant atmospheric calculations such as:
  
    - pressure, number density as function of altitude
    - gravitational constant as a function of latitude and altitude
    - modelling of Rayleigh extinction and atm. refractive index for variable atm. CO2 amounts based on Bodhaine et al., 1999, *On Rayleigh Optical Depth Calculations* and references therein

11/04/2017
==========

1. Removed scipy from requirements in setup.py since it often causes problems when installing via pip

2. Cleared up requirements in setup.py

18/04/2017
==========

1. Slight improvements regarding flexibility when performing 3D plots
    