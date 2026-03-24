# Regression Analysis Using Advertising Dataset
Project Overview
This project explores Multiple Linear Regression by modeling the relationship between advertising budgets and product sales. It is part of a Probability and Statistics assignment for a BS in Cybersecurity.


Dataset Description
The analysis uses the Advertising dataset to predict revenue based on media expenditures:

Features: TV, Radio, and Newspaper advertising expenditures (in USD).

Target: Sales (in thousands of units).

Sample Size: 10 records were used for this analysis.

Mathematical Model
Using Python's sklearn library, the following regression equation was developed:

Sales=−1.545+0.075⋅TV+0.303⋅Radio−0.069⋅Newspaper

Evaluation Metrics
The model was evaluated using the following statistical measures:

Mean Squared Error (MSE): 13.20.


Root MSE (RMSE): 3.63.

Key Insights

TV and Radio advertising show a positive impact on product sales.

Newspaper ads demonstrated a weak negative correlation in this specific model.
