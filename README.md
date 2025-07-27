--Summary of Project Stages

1. Abstract
2. Literature Review
3. Initial Results and Coding
4. Final Report
5. Presentation

--Summary of Initial Results and Coding

1. Data Collection & Exploration-

Retrieved datasets from the UCI Machine Learning Repository.

Explored the data to understand features, target variables, and missing values.

Visualized key variables to identify patterns related to student dropout and success.


2. Data Preprocessing-

Cleaned data by encoding categorical variables.

Converted target labels into binary classes for dropout prediction.

Addressed class imbalance with techniques like SMOTE, undersampling, and oversampling.


3. Model Development-

Built a Logistic Regression model to predict student dropout.

Evaluated model performance using classification metrics (accuracy, precision, recall, F1-score) and confusion matrices.

Trained a Random Forest classifier to identify important features influencing dropout and graduation outcomes.


4. Regression Analysis-

Developed a linear regression model to predict students’ GPA based on academic features.

Transformed and scaled target variables to improve prediction accuracy.

Calculated RMSE to measure regression model performance.


5. Results Interpretation & Visualization-

Analyzed feature importance and model coefficients to identify key factors affecting dropout risk and academic success.

Created visualizations such as boxplots and bar charts to illustrate GPA distributions and feature impacts.



--Summary of Repository Contents
 
1. Data Descriptions of "Higher_Education_Students_Performance_Evaluation"-
Data summary, checking missing values, mean, standard deviation, Pearson Correlations between each variable to target column

2. Data Descriptions of "Data_Descriptions_Predict_Students'_Dropout_and_Academic_Success"-
Data summary, checking missing values, mean, standard deviation, visualizations

3. Q1_Analysis_Coding.ipynb / Q1_Technical_Report_Revised - 
Classification reports, confusion matrices, logistic regression coefficients, Random Forest, visualizations

4. Q2_Analysis_Coding.ipynb / Q2_Technical_Report_Revised - 
Classification reports, linear regression, feature importance scores, RMSE, visualizations

5. Q3 Analysis_Coding.ipynb / Q3_Technical_Report_Revised - 
SMOTE, oversampling, undersampling, logistic regression models, classification reports, visualization
