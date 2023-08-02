# Python-Healthcare-Project
Predicting whether the patients in the dataset have diabetes or not.

I worked on this capstone project towards completion of final assessment for Data Science course from Simplilearn. The aim was to analyze the datasets from NIDDK consisting of several medical predictor variables and one target variable (Outcome). Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and more. I created and trained a number of Machine Learning models using various classification algorithms for prediction of diabetes in patients and created a dashboard for visualization of parameters.

# Problem Statement:
- NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates knowledge about and treatments for the most chronic, costly, and consequential diseases.
- The dataset used in this project is originally from NIDDK. The objective is to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.
- Build a model to accurately predict whether the patients in the dataset have diabetes or not.

# Steps Followed:

Data Exploration:

1. Performed descriptive analysis. Understood the variables and their corresponding values - a value of zero does not make sense and thus indicates missing value for: • Glucose • BloodPressure • SkinThickness • Insulin • BMI
2. Visually explored these variables using histograms. Treated the missing values accordingly.
3. Created a count (frequency) plot describing the data types - integer and float, and the count of variables.
4. Checked the balance of the data by plotting the count of outcomes by their value.
5. Created scatter charts between the pair of variables to understand the relationships.
6. Performed correlation analysis. Visually explored it using a heat map.

Data Modeling:

1. Devised strategies for model building. It was important to decide the right validation framework.
2. Applied an appropriate classification algorithm to build a model. Compared various models with the results from KNN algorithm.
3. Created a classification report by analyzing sensitivity, specificity, AUC (ROC curve), etc.

Data Reporting:

1. Created a dashboard in tableau by choosing appropriate chart types and metrics useful for the business. The dashboard entails the following:
- Pie chart to describe the diabetic or non-diabetic population
- Scatter charts between relevant variables to analyze the relationships
- Histogram/frequency charts to analyze the distribution of the data
- Heatmap of correlation analysis among the relevant variables
- Created bins of age values: 20-25, 25-30, 30-35, etc. Analyzed different variables for these age brackets using a bubble chart.
