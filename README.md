# Predicting-Employee-Attrition-to-Reduce-Employee-Retention-
Predicting Employee Attrition to Improve Employee Retention

This dataset is from technology start-up. The company is currently being hit by a big problem, many employees have submitted their resignations but the company has not made a decision about it. As a data scientist, We will help the company to explain the current condition of its employees, as well as explore the problems that exist in the company that caused the employee to resign so that it can reduce the rate of resigning from employees, and can outline a strategy that can increase employee retention. 

This notebook will present descriptive findings from data using visualization and converting Machine Learning's model findings into a story.

Steps in this notebook:
1. Data Preprocessing: handle missing values, change invalid value, and drop unnecessary data, handle imbalance data with SMOTEENN, SMOTETomek, RandomUnderSampler, TomekLinks, EditedNearestNeighbours
2. Exploratory Data Analysis
* Percentage of Employees per Division Who Did Not Resign
* Number of Employees of Data Analyst Division based on Career Path, Performance, and Recent Conditions in the Company
* Percentage of Employees Resigned based on their Reasons and Job
4. Machine Learning: We will use 13 model classifier
5. Insight: Insight will be explored using the method Partial Dependence Plot, SHAP, and Feature Importance

After the modelling, we can get information:
1. ![image](https://user-images.githubusercontent.com/84758353/180114092-e1bdca9c-98bc-40c6-986b-292715890076.png)

1. The chance of resigning an employee if he is over 45 will increase by 5 to more than 20 percent compared to employees who are in the younger range. Especially if the current employee is over the age of 52, the chance of resigning will be very high (> 50%)
2. Based on the engagement survey score, employees who write a score of 2 to 5 have a higher chance of resigning than those with a score of 1.
3. Based on the number of employee absenteeism, employees who have an absence rate of more than 5 days, have a greater chance of resigning than before 5 days.
4. Based on the number of project participation, the more often employees are included in the project it turns out to be less good for them so that their chances of resigning will be higher, especially if there are more than 4 projects they will have a higher potential to resign than those who don't.




Acknowledgment: 
This project's dataset is given by Rakamin Academy
