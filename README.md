# 1.0 Adaptive Design Optimization (ADO)
An application of ADO to assessment centers (AC)

# 2.0 Description
ADO is a model-based approach to optimization in that it uses a quantitative model to predict outcomes based on the model's parameters and design variables. ADO uses these predictions to quantify the expected information that would be gained by gathering further observations. In this way, ADO can be used to adjust design variables in real-time to optimize the value of information gained.

The code in this repository applies ADO to assessment centers (AC), a method to appraise and predict behavioral performance. During an AC, a candidate completes a series of simulation exercises. Evaluators rate the candidate along behavioral dimensions thought to reflect abilities and traits that contribute to performance for a particular job or career field.

The cost of the AC, in terms of compensation and time for candidates and evaluators to complete exercises and assessments, may prohibit its use. This project demonstrates how to use ADO to increase the efficiency and validity of behavioral rating in the AC.

# 3.0 Table of Contents
The main file for running the simulation is the R Notebook, runADO.rmd, contained in the src subdirectory. The notebook calls functions contained in the utilities subdirectory, and writes to the inputs subdirectory.

# 4.0 Running the Simulation
To run the simulation, select the R Notebook, runADO.rmd.

The simulation was developed in R version 3.6.3 and uses several packages installed from CRAN: tidyr; dplyr; ggplot2; matrixStats; and parallel.

# 5.0 Citations
Walsh, M. M., Gluck, K. A., Gunzelmann, G., Jastrzembski, T., Krusmark, M., Myung, J. I., ... & Zhou, R. (2018). Mechanisms underlying the spacing effect in learning: A comparison of three computational models. Journal of Experimental Psychology: General, 147(9), 1325.

Myung, J. I., Cavagnaro, D. R.,& Pitt, M. A. (2013). A tutorial on adaptive design optimization. Journal of Mathematical Psychology, 57, 53-67.
