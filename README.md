# DEM_PFC2D_Bransby-et-al-2008_Sandbox
This is the general Particle Flow Code 2D (PFC2D v7.0) to replicate the analog sandbox fault model in Bransby et al., (2008) as well as the 3D DEM models in Garcia &amp; Bray (2018).  

# README
Each set of project files contains everything required to reproduce a model in Particle Flow Code (PFC2D) version 7.00.152 or later. The main project file (pfc2d_project_Bransby.p2prj) will open the required data files attached and contain a series of plots to visualize the model (generally the particles and contact bonds) in PFC2D. The models can be run from the command line or iPython console. The fish functions file defines each of the fish commands required for a model (e.g., defining the boundary conditions, generating pregrowth layers, making a fault, running the deformation sequence). The parameter_def file contains each of the numerical parameters that are modified for each of the trials (e.g., model width, particle radii, cohesion and tensile strength of contact bonds, etc). The run file calls each of the parameters and fish functions in the order required for a full generation of sediment and deformation sequence. Sediment will need to be generated first as an unbonded.sav file. This can be done using the run file and calling each of the fish functions. 
