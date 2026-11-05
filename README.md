# Enzymatic_dynamic_forecasting
A repository of code relating to the publication Dynamic Forecasting with an Enzymatic Reservoir Computer, Anna C. Knox, Souvik Ghosh, Wilhelm T. S. Huck.

Reqires python v3.13

```bash
conda env create -f environment.yml
```

# Running 

To activate the environemnt:

```bash 
conda activate enz_dynamic_forecast_env
```

# Structure

- data includes the preprocessed ion traces alongside the input conditions and time for each task
- preprocessed_data contains the preprocessed data generated and the plots used in creating figures 2-4 main text and supporting figures S2-4
- scripts contains:
    - csv files containing the task inputs that were applied to the network and used in training 
    - scripts to train a linear regression and apply the generated weights to predict a point ahead and plot those predictions
    - a script to use the generated predictions to plot the low and high resolution data on the same figure for comparison purposes (figure 3)