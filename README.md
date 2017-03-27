# Macroeconomic Dynamics Near the ZLB: A Tale of Two Countries

Replication Files for: 

"Macroeconomic Dynamics Near the ZLB: A Tale of Two Countries"
Review of Economic Studies. (Forthcoming)

by

Boragan Aruoba (Maryland)
Pablo Cuba-Borda (Board of Governors)
Frank Schorfheide (Penn)

This repository consists of 4 directories:

1) DSGE Estimation: contains MATLAB/DYNARE code to generate the parameter
estimates that are reported in the paper and used for the subsequent
empirical analysis. 

2) Solution: contains MATLAB code to solve the nonlinear DSGE models 
with ZLB constraint considered in the paper. Please note that construction
of the grids that are used for the model solutions is based on a "manual"
iteration of the solution and the filtering programs. The replication files
use the grid obtained in the last iteration of this process. 

3) Filtering: contains GAUSS programs that implement a version of the particle
filter to extract the hidden states associated with the nonlinear DSGE model.
The GAUSS programs take the model solutions generated under 2) as an input.

4) Analysis: contains MATLAB and R programs to generate the figures in the paper. 
Note that these programs are self-contained in the sense that each figure 
subdirectory contains a file with the relevant output from the model solution 
and filtering programs. The information in the spreadsheets in
/solution/solutions for filter/ 
corresponds to the information in the 
/filtering/***model id***/input
/filtering/***model id***/results
directories.
