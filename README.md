<div align="center"> <h1> WHO Life Expectancy Prediction Model Report</h1> </div>
<img src="https://data.org/wp-content/uploads/2024/01/WHO_logo.svg" style="width:100%; height:200px; object-fit:cover;" />
The objective of this project was to create a robust predictive model using linear regression with a low margin of error. 
The report notebook contains all of the data explorationa and analysis in full as detailed by the table of contents below. The function notebook contains the life expectancy function, which will predict life expectancy when executed.

### Table of Contents  
 - 01: Exploratory Data Analysis  
 - 02: Modelling  
 - 03: Function  
 - 04: Conclusions

This was a team project but improvements and changes have been made so that the function can be ran without the life expectancy data and rerunning the linear regression model. More exception handling was also added individually.
Some key findings were:
- High levels of multicolinearity.
- Positive correlation between life expectancy, schooling and various vaccinations.
- Negative correlation between life expectancy and deaths (which is to be expected).
- Scaling will be needed for some columns.

The linear regression model was created using the following steps:
 - Train/test split
 - Feature Engineering
 - Statistical Model: Basic
 - Statistical Model: Optimised

Key Results:
- Basic Model: Using the training data, life expectancy is accurately predicted within 2.79 years.
- Basic Model: Using the test data, life expectancy is accurately predicted within 2.69 years.
- Optimised Model: Using the training data, life expectancy is accurately predicted within 1.24 years,
- Optimised Model: Using the test data, life expectancy is accurately predicted within 1.21 years.
- Basic Model had an excellent condition number (19.7) indicating very low levels of collinearity in the modelling and general numerical issues.
- Optimised model had a excellent condition number with a value of 22.5.


