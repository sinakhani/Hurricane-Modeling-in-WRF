- This directory includes data for high and coarse-resolution Hurricane simulations for Harvey (2017) and Ida (2021)\\
  using Weather Research and Forecasting (WRF) model.

- This is an open access dataset under the terms of the Creative Commons Attribution License, which permits \\
  use, distribution and reproduction in any medium, provided the original work is properly cited.

- For reference, please cite the following paper:
  Sina Khani and Clinton N. Dawson. Potential vorticity diagnostics of hurricane movement: case studies for Hurricanes Harvey (2017) and Ida (2021),\\
  Journal of Atmospheric Sciences, (2023), Submitted.

- NETCDF files are listed below, and inculde discretizations for r: longitude x, p: latitude y, l: time, q: vertical pressure level z.

Pot_Temp : Potential Temperature T

Precipt  : Accumulated Precipitation    

Pressu   : Pressure P

PV       : Potential Vorticity Q

PVX      : DQ/Dx 

PVY      : DQ/Dy

WindVel  : Wind Velocity at the surface U10 and V10 (includes zonal velocity U and meridional velocity V)

UVel     : Wind Velocity at all vertical levels     (includes zonal velocity U and meridional velocity V)

UPVY     : U*DQ/Dy             

wrfout   : All WRF output variables

GrT      : Temperature gradient DT/Dz  

Vortz    : Absolute vorticity 

- d02 and d01 tails denote nest and main domains (see Khani and Dawson 2023). 
- HHar and HIda denotes Harvey and Ida simulations.
- 15km5km tail denote the coarse-reoslution simulation.  

### To access outputs of WRF simulations and NETCDF files, please contact: sina.khani@austin.utexas.edu, or skhani@princeton.edu, or sina.khany@gmail.com
