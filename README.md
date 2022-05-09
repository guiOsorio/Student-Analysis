# Student-Regression-Analysis

The goal of this project is to try to explain which variables are important when predicting a student's academic success.

## This project was divided in the following way:
- ### Data Collection
  - The dataset used in this analysis was obtained from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Student+Performance).
- ### Data Cleaning & Preprocessing
  - Explored the data to gain familiarity with the dataset, using the Python libraries matplotlib and seaborn (for visualizations), and pandas and numpy for exploratory data analysis
  - Created and transformed variables to fit the machine learning models using the Python libraries pandas and numpy
- ### Regression Models - Implementation and Evaluation
  - Linear Regression model predicting final grade, using Python library statsmodels
    - Adjusted r-squared of 10.6% for math discipline
    - Adjusted r-squared of 22.2% for portuguese discipline
  - Logistic Regression model predicting pass/fail, using Python library statsmodels
    - Pseudo r-squared of 6.1% for math discipline
    - Pseudo r-squared of 21.3% for portuguese discipline
- ### Conclusion
  - Interpreting and reporting the findings of the analysis, included in the Jupyter Notebook
