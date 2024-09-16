Project Title:
Loan Default Prediction – Data Understanding Phase for Lending Club

Executive Summary:
Objective:
This project focuses on improving Lending Club's loan repayment predictions by analyzing the factors influencing the likelihood of customers paying back their loans. This report specifically covers the Data Description and Data Exploration phases to provide insights into the loan dataset, with the aim of identifying key variables impacting loan repayment outcomes.

Context:
The data for this project is provided by Lending Club and contains a variety of loan features, borrower information, and credit bureau data. Tools used include Tableau for visualizations and Excel for basic statistical analysis.

Business Problem:
Problem Identification:
The challenge is to improve Lending Club's ability to predict loan repayment behavior. Understanding which factors contribute to loan defaults or successful repayments will help the company mitigate risks and make informed lending decisions.

Business Impact:
Accurately predicting the likelihood of loan defaults is critical for minimizing financial losses, maintaining a healthy loan portfolio, and enhancing customer satisfaction by offering fair lending terms.

Methodology:
Data Cleaning & Transformation:

The loan_status_numeric feature, which ranks loan repayment status, is used as the target variable.
Missing values in variables such as emp_length and mths_since_last_delinq were addressed by removing or imputing values where appropriate.
Categorical data, such as grade and purpose, were standardized for analysis.
All relevant numerical and categorical variables were summarized for further exploration.
Analysis Techniques:

Descriptive statistics were generated for key variables, including loan_amount, annual_income, and dti (debt-to-income ratio).
Visual exploration using Tableau included bar charts and box plots to identify relationships between loan repayment status and other factors.
Correlation analysis was performed to identify relationships between variables like interest rate, employment length, and loan default rates.
Skills:
Tools, Languages, & Software:

Tableau for data visualization and trend analysis.
Excel for data cleaning and statistical summaries.
Results & Business Recommendations:
Business Impact:
The initial exploration highlighted significant relationships between certain borrower attributes, such as homeownership status, employment length, and debt-to-income ratio (DTI), and loan default rates. Loans with high DTI and low credit grades were found to be at greater risk of default.

Insights:

Customers with shorter employment histories (less than 1 year) were more likely to default.
Higher interest rates were linked to a greater likelihood of loan default.
Borrowers with low revol_util (credit utilization) tend to have better repayment behaviors.
Loans categorized as fully paid were associated with lower debt-to-income ratios.
Next Steps:
Future Work:

Investigate more granular trends within borrower sub-groups, particularly focusing on income verification status.
Conduct further analysis using predictive models (e.g., logistic regression) to quantify the risk associated with various borrower attributes.
Explore additional features such as sub_grade and total_rec_prncp for better prediction accuracy.
