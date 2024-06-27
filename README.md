# software_sales_date
Dataset that simulates software sales data for a global IT company. Analyzed the data to identify trends, provide insights into sales performance, and suggest actionable strategies in PowerBI
--------------------------------------------------------------------------------------------------

Introduction

The main objective of data analysis assignment is to analyze software sales data for a global IT company. The analysis aims to identify trends, provide insights into sales performance, and suggest actionable strategies to improve sales outcomes. The tasks include data cleaning, exploratory data analysis, data visualization, predictive modeling, and reporting insights and recommendations.
--------------------------------------------------------------------------------------------------

Data Cleaning and Preparation

Data Cleaning and Preparation
Applied dropna() method to remove null values
Build date converter function to maintain single date format for ‘Date of Sale’ column
Changed data types for a few columns (for smooth calculation).

To gain key findings from descriptive analysis, and to observe trends and patterns.
Used seaborn libraries 'line plot’ to visualize sales trends over time(Quarter)

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/5b9a30b0-e76c-4d43-8a31-3148fe0f6e05)

We have used bar graph to analyze best performing region
In x axis we have selected ‘region’ and in y axis ‘Sales Amount’

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/5dd6787c-2605-4331-ba4b-4c339f8e4a8f)

To identify the customer's purchase pattern we have used below method.

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/cd702aa7-a64c-40c5-9afe-f9cafca49556)

--------------------------------------------------------------------------------------------------

Data Visualizations

To illustrate sales trends, distribution across categories, and notable correlations, we have used a variety of charts and visualizations in Power BI.

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/799d3dcc-5639-424e-9d03-fd14cd043a3b)

--------------------------------------------------------------------------------------------------

Predictive Modeling

Have implemented a Decision Tree Model.
It indicates the Mean Absolute Error(MAE) [absolute differences between the predicted and actual values] and Root Mean Squared Error(RMSE) [square root of the squared differences between the predicted and actual values] values indicate how well the model fits the data.
Despite the high error metrics, the model forecasts increasing sales for the next quarter, suggesting a positive trend in sales for the upcoming quarter.

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/9b17095e-7edc-473b-822b-ab3a306cae7a)

![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/5956470c-e595-4a05-873d-a5ab819b5a16)

The MAE is 24,835.33, this means that, on average, the model's predictions are off by about $24,835.

The RMSE of 27,451.06 indicates that the model's predictions are generally off by this amount.

The model predicts sales for the first quarter of 2023 to be approximately $1,590,179 for each month.


![image](https://github.com/winstonrebello/software_sales_date/assets/63299212/dd218bff-c193-4376-a949-1c718a3adc91)

