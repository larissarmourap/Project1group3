# Project1group3

# Predictors of Pregnancy Risk

Alexis Rojas
Larissa Fierle
Natalie Lopez
Maria Villacreces

Our research aims to identify the key indicators that influence risk levels during pregnancy. We are using datasets from various hospitals, clinics and maternal health cares in Bangladesh, India. Our primary focus is analyzing age, blood pressure, and blood sugar to determine their impact on predicted risk intensity level of pregnancy complication.

OUTLINE:
1.	Which health conditions are the strongest indications for health risks during pregnancy?
2.	How much blood pressure is safe during pregnancy?
3.	How do Blood glucose levels (mmol/L) affect the risk level during pregnancy?
4.	How does age correlate with the risk level? We can categorize (<20, 20-30, 31-40, 41-50, >50)
5.	Does a pregnant woman's heart rate predict her pregnancy risk level?

REFERENCES:
https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data?resource=download


# STEPS:

Setting dependencies and setup.
Specifying path to .csv file and reading .csv file.
Counting each risk level for raw data.
Dropping duplicate data.
Counting each risk level for clean data.
Adding a new column “Woman_ID” with unique identifiers.
Renaming columns got better understanding.
Create a new column "Blood Pressure".

# Blood Pressure VS Risk Level
Hypothesis:
Women who have high blood pressure are at a higher risk than women who are within the normal blood pressure range.

Create a dataframe for Woman ID, Age, Systolic Blood Pressure, Diastolic Blood Pressure, Blood Pressure.
Define bins for Systolic and Diastolic BP.
Create a line plot for BP.
Create a pie chart for BP.
Calculate t-test.

# Blood Sugar VS Risk Level
Hypothesis:
Elevated blood glucose levels in pregnant women are associated with an increased risk of complications, categorizing the pregnancy as higher risk

Create a dateframe for Woman ID, Age, and Blood Sugar.
Define bins for blood sugar and age.
Generate a bar graph for Blood Sugar.
Generate a scatter plot for Blood Sugar.

# Age VS Risk Level
Hypothesis:
The age of a woman significantly influences her risk level during pregnancy, with specific age groups showing a higher chance.

Generate a summary statistics.
Find Quartiles and Outliers.
Generate a boxplot for Age.

# Heart Rate VS Risk Level
Hypothesis:
The resting heart rate of a woman during pregnancy correlates with the risk level of the pregnancy. Certain heart rates could suggest whether her pregnancy is at a higher or lower risk.

Create a dataframe for Woman ID, Age, and Heart Rate.
Define bins for heart rate.
Generate a bar plot for heart rate.

# Display Bangladesh, India on the Map

Create the target city and endpoint URL.
Run a request to endport and convert to json.
Print json in pretty print.
Extract latitude and longitude.
Set the geographical coordinates for Bangladesh, India.
Set the parameters.
Create the base URL.
Create hospital dataframe.
Configure the map.

# Final Analysis
Our study found blood pressure to be the strongest indicator of pregnancy risks, surpassing age, heart rate, and blood sugar. The importance of managing blood pressure is shown by our significant findings, with a p-value of 1.39e-23, indicating a strong relationship between blood pressure and pregnancy risk levels. Overall, this highlights the necessity of prioritizing blood pressure monitoring to ensure the safety of both the mother and child during pregnancy.
