## Team: PM

# Project Description
  ## Introduction
  The truth is that we are surrounded by machines from a toaster every morning to an airplane every summer holiday that make our life easier, but we also get more and more dependent on them. When the impact of a failure cannot be afforded, the machine is subjected to preventive maintenance, which involves periodic inspection and repair.
  
  ## What it does? 
  > What are the inputs/outputs? How does it work?
It makes predictions which future the machine will have in terms of failure or successful.  Also, it makes predictions which component will be failure.
  
  ## Challenges
  > Difficulties encountered
 
Merging dataframes and creating new columns for feature engineering.
 ## Achievements
 > Progress, accomplishments
 
  ## Future work
 Regression models to predict remaining useful lifetime (RUL) and flagging anomalous behaviour
  
# Data 
 > Detailed data description
Data are obtained from following link https://notebooks.azure.com/Microsoft/projects/PredictiveMaintenance/html/Predictive%20Maintenance%20Modeling%20Guide%20Python%203%20Notebook.ipynb
 
 The first data source is the telemetry time-series data which consists of voltage, rotation, pressure, and vibration measurements collected from 100 machines in real time averaged over every hour collected during the year 2015. Below, we display the first 10 records in the dataset. A summary of the whole dataset is also provided.

The second major data source is the error logs. These are non-breaking errors thrown while the machine is still operational and do not constitute as failures. The error date and times are rounded to the closest hour since the telemetry data is collected at an hourly rate.

The third source is about the maintenance. These are the scheduled and unscheduled maintenance records which correspond to both regular inspection of components as well as failures. A record is generated if a component is replaced during the scheduled inspection or replaced due to a breakdown. The records that are created due to breakdowns will be called failures which is explained in the later sections. Maintenance data has both 2014 and 2015 records.

The fourth data set includes some information about the machines: model type and age (years in service).

The last data the records of component replacements due to failures. Each record has a date and time, machine ID, and failed component type.
 
 > Resource
# Folder Structure
 > Repository folder structure
 The whole dataset that we have created in the following link  https://drive.google.com/drive/folders/1eAEtl8huBkUr1C5oMV--C4MziCK6Yv6T?usp=sharing
 
# Requirements
> Software, packages etc.
Numpy, Pandas, matplotlib, sklearn,matplotlib.pyplot, seaborn.

# How to Run
> How to run from the command line? How to reproduce the results?  How to test your system? 

# References
https://notebooks.azure.com/Microsoft/projects/PredictiveMaintenance/html/Predictive%20Maintenance%20Modeling%20Guide%20Python%203%20Notebook.ipynb

