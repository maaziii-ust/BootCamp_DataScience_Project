Student Performance Analysis & Prediction

Project Overview: 
This project evaluates performance of student on the basis of given data and builds a linear regression model to predict the final scores. Complete pipeline o  data Science is followed which includes data cleaning, visualization, feature engineering and model evaluation.

Dataset Description: 
The dataset provided contain record of 205 students with features such as:
- Age
- Gender
- City
- Department
- Attendance
- Study Hours
- Assignments, Quizzes, Midterm marks
- Internet Access
- Education Level

Target Variable:
- Final_Score

Data Cleaning
- Fixed inconsistent casing
- Converted Age to numeric
- Handled missing values using median
- Removed impossible values
- Removed duplicate rows

Exploratory Data Analysis
- Distribution of Final Score
- Attendance vs Final Score
- Study Hours vs Final Score
- Midterm vs Final Score
- Correlation Heatmap
- Department-wise analysis

Feature Engineering
- Created Total_Academic
- Created Attendance_Category


Encoding & Scaling
- One-Hot Encoding: Gender, City, Department, Internet_Access
- Ordinal Encoding: Education_Level, Attendance_Category
- StandardScaler used for numerical features


Model
- Linear Regression
- Built using sklearn Pipeline


Model Evaluation
- MAE: (write your value)
- RMSE: (write your value)
- R² Score: (write your value)


Conclusion
The model learned that overall academic performance has the strongest impact on Final_Score.The R² score shows that the model explains a good portion of the variation, but improvements can be made by adding more features.---

Author
Maaz Siddique
