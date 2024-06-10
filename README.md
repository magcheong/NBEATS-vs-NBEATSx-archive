# NBEATS-vs-NBEATSx-archive

This project was initially for project module for Specialist Diploma in Appled AI course. The outcome of the project was not gratifying as the optimisation on NBEATS did not manage to resolve errors observed in the predictions. A quick test on NBEATSx at that time did not manage to produce better results. Due to time constraint from project deadline, NBEATSx could not be further evaluated. The re-evaluation done this time round was to revisit the optimsation by Optuna for NBEATS and give NBEATSx a deeper evaluation. This re-evaluation has also considered many more hyperparameters. 

Due to the number of hyperparameters involved, parameters like max_length and input_size are first evaluated to locate the estimated point of operation. For the remaining hyperparameters, the methodology adopted is elimination by identifying trends from the results collected (excel sheet) over several iterations. Then factors like learning rate, max_steps and input_size are then re-evaluated in an attempt to find the optimal process.

The evaluation process is done using Optuna hyperparameter tuning. Though the direction is set for Optuna to head for minimal error, it is not able to provide sense of how each hyperparameter affect, hence extensive runs were done to get a feel of the trend. 
