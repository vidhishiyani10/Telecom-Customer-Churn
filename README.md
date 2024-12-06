# Telecom-Customer-Churn
This particular project is based on EDA and training model to predict the reasons for customers churning due to any reason. This project is more focused towards detailed EDA and model evaluation.

Perform Explanatory Data Analysis (EDA) on Customer Churn data within the Telecommunication industry. Although there will be no need to build a model based on the data provided, you are asked to look for issues in the data and find correlation among the various variables in order to improve/lower customer churn predictions.

What is Churn Rate ?
Churn rate is a critical metric of customer satisfaction. Low churn rates mean happy customers; high churn rates mean customers are leaving you. A small rate of monthly/quarterly churn compounds over time. 1% monthly churn quickly translates to almost 12% yearly churn.

Instructions
Investigating the data should be done two-fold:

Manually by utilizing the classic (legacy) EDA libraries: NumPy, Pandas, graph libraries (MatPlotlib, Seaborn, Plotly), and Python’s Statsmodel modules.
Generate ‘html’ reports by integrating Pandas Profiling and SweetViz Python libraries.
The analysis of the data should focus on predicting customer churn rate.

To run the code;
Add the dataset telecom-customer-churn
Import the following libraries : import numpy as np import pandas as pd import matplotlib.pyplot as plt %matplotlib inline import seaborn as sns import statsmodels.api as sm
file_path = 'Path of your dataset' telecom_df = pd.read_csv(file_path)
