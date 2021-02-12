# wind_energy
Application of PGML for wind energy control applications.

## PGML
- Model V0: PGML surrogate model for Xfoil forces prediction with Panel method as the simplified model.
- Model V1: PGML surrogate model for CFD forces prediction (from OpenFoam) with Xfoil solver as the simplified model.
- Model V2: Take into account uncertainties in airfoil shape in the prediction of lift and drag coefficient

## CFD Simulation
- Validate CFD model for particular Airfoil from the IEA-15 MW turbine (for example FFA-W3-301)
- Python scripts to automate running multplie CFD simulations in OpenFoam 

## Wind turbine model
- Given the lift and drag coefficient for two-dimensional airfoils based on the angle of attacks and velocity of the flow, how to compute forces for three-dimensional wing...
