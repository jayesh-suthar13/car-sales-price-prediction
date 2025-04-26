# car-sales-price-prediction
This project predicts car prices using Linear Regression and segments similar cars using Clustering techniques. It helps in understanding price patterns and grouping vehicles based on features for better market insights.

Car Sales Price Prediction
A machine learning project focused on predicting car purchase amounts using Linear Regression and segmenting customers with K-Means Clustering.
The dataset used is clean, containing no missing values and no duplicate records.

Project Overview
In this project, we analyze customer data to predict the amount they are likely to spend on purchasing a car.
Additionally, we cluster customers into groups based on their financial and demographic characteristics to gain deeper market insights.

Exploratory Data Analysis (EDA)
The EDA process included:

Gender Distribution
Analyzed the distribution of male and female customers to understand demographic balance.

Feature Distributions
Visualized the distribution of key numerical features:
Age
Annual Salary
Net Worth

Pair Plot of Numerical Features
Explored relationships between:
Age
Annual Salary
Credit Card Debt
Net Worth

Scatter Plots:
Annual Salary vs. Net Worth: Investigated how annual earnings relate to total net worth.
Annual Salary vs. Car Purchase Amount (colored by Gender): Studied how salary impacts car purchases across genders.

Join Plot: Annual Salary and Net Worth
Created a joint distribution plot to further examine the relationship between annual salary and net worth.

Correlation Matrix
Computed feature correlations with key findings:
Age and Car Purchase Amount: 0.6328 — Strong positive correlation.
Annual Salary and Car Purchase Amount: 0.6178 — Strong positive correlation.
Net Worth and Car Purchase Amount: 0.4885 — Moderate positive correlation.

Data Preprocessing
Feature Scaling
Standardized the features to ensure all input variables contributed equally to the model.

Train-Test Split
Divided the dataset into training and testing sets to evaluate model performance effectively.

Modeling
Linear Regression
Developed a linear regression model to predict car purchase amounts based on customer features such as age, salary, credit card debt, and net worth.

K-Means Clustering
Applied K-Means clustering to segment customers into groups based on financial and demographic similarities, providing actionable insights for targeted marketing.

Results
The Linear Regression model effectively predicted car purchase amounts with a good level of accuracy.

K-Means Clustering identified distinct customer groups, helping to better understand customer behavior and purchasing power.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
