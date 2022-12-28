
# Salary Estimator - Using Machine Learning: Project Overview

1) Created a machine learning model to estimate the salary which helps one to negotiate their income based on the job description, job location and many other aspects.'

2) Performed data cleaning, data manipulation, data preprocessing, exploratory data analysis and built a machine learning model.

3) Optimized the Linear, Lasso, Random Forest Regressor using GridSearchCV to reach the best model.



## Code Used

- **Packages** : pandas, numpy, sklearn, matplotlib, seaborn
- **IDE** : Jupyter Notebook

## Data Cleaning

Data cleaning has been performed to make the dataset useful for model creation. The following changes have been implemented:

- Analyzed the numeric data.
- Columns have been created for hourly and employer_provided salary.
- Columns have been created for min_salary and max_salary.
- Average salary column has been added.
- Removing rating out of company_text.
- State column has been created using state's initials.
- Checked if the job was at the company's headquarter or not.
- Transformed the founded date into the age of the company.
- Made columns for if different skills were listed in the job descriptions:
    * Python
    * R
    * Excel
    * AWS
    * Spark
- Column for smplified job and seniority
- Column for job description length


## Exploratory Data Analysis

Below are some of the insights which have been driven from the dataset:

- *Correlation*

![alt text](https://github.com/udit2895/data_science_proj/blob/7b2b0d93f8395ea6965e863126833fa4120f5d5d/Corr_features.png?raw=true)

- *Number of Jobs* 

![alt text](https://github.com/udit2895/data_science_proj/blob/7b2b0d93f8395ea6965e863126833fa4120f5d5d/Number_of_jobs.png?raw=true)

- *Location based jobs*

![alt text](https://github.com/udit2895/data_science_proj/blob/7b2b0d93f8395ea6965e863126833fa4120f5d5d/Location_based_jobs.png?raw=true)

- *Job Title vs Avg Salary*

![alt text](https://github.com/udit2895/data_science_proj/blob/facfba19ff1d65dd2d7336bfeeffffb57bc4431d/Job_title_vs_Avg_Salary.JPG?raw=true)

- *Job Title / Seniority vs Avg Salary*

![alt text](https://github.com/udit2895/data_science_proj/blob/7b2b0d93f8395ea6965e863126833fa4120f5d5d/Job_title_seniority_avg_salary.PNG?raw=true)


## Model Building

- Converting categorical variable into dummy variables and spliting the dataset into training and testing with the test size of 20%.

- Following machine learning models have been used and evaluated based on thier MAE values.
    - Multiple Linear Regression
    - Lasso Regression
    - Random Forest


## Model Performance

The Mean Absolute Error for Random Forest model is better than the Multiple Linear Regression and Lasso Regression model which is:

**Random Forest MAE** = 12.97
 

# Hi, I'm Udit Agrawal! 👋


## 🚀 About Me
I am a graduate student at the University of Texas at Dallas, pursuing Master's in Information Technology and Management with the Data Science track.

I am passionate about the field of management, business intelligence and statistics and keen to learn about evolving technologies. The amalgamation of both technology (specifically in statistics) and management inclined my interest towards the Data Science roles.



## 🔗 Links
[![portfolio](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/udit2895)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/uditagrawal28/)



## 🛠 Skills
- Python: #pandas, #numpy, #matplotlib, #scikit-learn, #seaborn
- R
- SQL
- NoSQL 
- Tableau
- Machine Learning: #Regression, #clustering analysis, #Support Vector Regression, #gradient-boosted tree

