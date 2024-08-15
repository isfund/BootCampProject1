# Home Purchasing Forecast 
**Overview:** Studying the effects of including household income, student loan debt, mortgage rates and price of homes on homebuying rates in the U.S. between late 1900's and early/mid 2000's. By analyzing the effect of these key factors on the housing market we will be able to forecast a homebuying trend for a future decade based key factors that is most correlated with historic home purchases. 

_Analysis includes the following steps:_
1. Gathering data and create CSV files 
2. Loading the data from CSV files into pandas DataFrames.
3. Descriptive Statistics: Calculating the mean, median, standard deviation, and other descriptive statistics for both datasets.
4. Correlation Analysis: Performing a correlation analysis between the average student loan debt and the average number of homes sold per year.
5. Regression Analysis: Performing simple linear regression analysis between average student loan debt and the average number of homes sold per year.
6. Visualization: Creating various plots to visualize the data, including:
      - Line graph showing the number of homes sold over the years with student loan debt and a regression line.

**Table of Contents**
1. Dependecies
2. Installation Instructions
3. Features
4. Acknowledgements

**Dependencies:**
1. Pandas
2. Matplotlib.pyplot
3. Sklearn.linear_model
    LinearRegression 
4. Numpy
5. Datetime
6. Scipy.stats
    Linregress
    ttest_ind   
8. CSV
9. Scipy
    stats

   
**Installation Instructrions:**
* Clone repository locally
* Activate dev enviornment via Anoconda
* Open project with Jupyter Notebook 

**Features:**
Correlations between Homebuying and
1. Household Income
2. Mortage Rates
3. Student Loan Debt
4. Price of Homes 
      
**Acknowledgements**
Datasets were sourced from: 
* `MEHOINUSA672N.csv` : https://fred.stlouisfed.org/series/MEHOINUSA672N
* `average_number_of_house_sold_by_year_output.csv`
* `average_student_loan_debt.csv` : https://thecollegeinvestor.com/32031/average-student-loan-debt-by-year/
* `MSPUS.csv` : https://fred.stlouisfed.org/series/MSPUS
* Mortgage Rate Data: https://fred.stlouisfed.org/series/MORTGAGE30US
* Number of Homes Bought per year: https://www.census.gov/construction/nrs/historical_data/index.html
* average_student_loan_debt.csv:https://thecollegeinvestor.com/32031/average-student-loan-debt-by-year/




