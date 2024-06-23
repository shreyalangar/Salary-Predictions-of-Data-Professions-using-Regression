# Salary-Predictions-of-Data-Professions-using-Regression
In this project, we will dive into the world of regression tasks and gain hands-on experience in data analysis, feature engineering, and machine learning model development using various regression algorithms.

**Objective:**
Salaries in the field of data professions vary widely based on factors such as experience, job role, and performance. Accurately predicting salaries for data professionals is essential for both job seekers and employers.

The goal is to predict the salaries of data professionals based on a rich dataset.

**Dataset:**
The dataset contains 2639 rows and 13 following columns:

1. FIRST NAME : First name
2. LAST NAME : Last name
3. SEX : Gender
4. DOJ : Date of joining the company
5. CURRENT DATE : Current date of data
6. DESIGNATION : Job role/designation
7. AGE : Age
8. SALARY : Target variable, the salary of the data professional
9. UNIT : Business unit or department
10. LEAVES USED : Number of leaves used
11. LEAVES REMAINING : Number of leaves remaining
12. RATINGS : Ratings or performance ratings
13. PAST EXP : Past work experience

**Steps:**

**1. Exploratory Data Analysis (EDA):** Dive into the dataset, conduct comprehensive EDA, and unveil valuable insights about data professionals' salaries. EDA involves:
    1. Reading the dataset
    2. Finding shape and information about the dataset
    3. Summary statistics
    4. Identifying patterns in the data

**2. Data Preprocessing:** Prepare the raw data and make it suitable for a machine learning model. This includes :
    1. Finding and handling missing values
    2.  Dropping irrelevant columns
    3.  Encoding categorical variables
    4.  Scaling or normalizing features as needed

**3. Feature Engineering:** Create new features or transform existing ones that can provide additional insights or improve model performance. Feature engineering might involve deriving features related to experience, job role, and performance. Derived features:
    1. Calculate job tenure (TENURE) from CURRENT DATE and DOJ columns
    2. Calculate total years of experience (TOTAL EXP) from TENURE and PAST EXP
    3. Calculate PERFORMANCE POTENTIAL based on RATINGS and TENURE
  
**4. Data Visualization:** Data visualization is an essential step in data preparation and analysis as it helps to identify outliers, trends, and patterns in the data that may be missed by other forms of analysis. It includes:
    1. Libraries like matplotlib, seaborn, etc.
    2. Bar charts, pie charts, scatter plots, violin plots, box plots and pair plot
    3. Correlation matrix
  
**5. Machine Learning  Model Development:** Train various machine learning regression models to predict salaries. Experiment with different algorithms such as linear regression, decision trees, random forests, and gradient boosting to find the best-performing model. This step involves:
    1. Splitting data into train and test sets
    2. Choosing appropriate ML algorithm
    3. Building ML model with training data
  
**6. Model Evaluation:** Assess the performance of your models using appropriate evaluation metrics such as:
    1. Mean Absolute Error (MAE)
    2. Mean Squared Error (MSE)
    3. Root Mean Squared Error (RMSE)
    4. R-squared (R2) score

**Algorithms Used:**

A set of supervised (for labelled data) and unsupervised (for unlabeled data) algorithms are available to choose from depending on the nature of input data and business outcome to predict. 

In this project, we are using regression models as below:
1. Linear Regression
2. KNN
3. Decision Tree
4. Random Forest
5. Ada-boost
6. Gradient-boost

**Final Takeaways:**
1. Based on the metrics’ results, Linear Regression appears to perform slightly better in terms of MSE and MAE compared to the other models.
2. However, Random Forest, AdaBoost, and Gradient Boosting also demonstrate strong performance with similar R2 scores and slightly higher MSE and MAE values.
3. It's essential to consider both the accuracy and interpretability of the models when selecting the most appropriate model for salary prediction.
4. Based on the provided evaluation metrics, the models can be ranked from best to worst performance as follows:
   
**Linear Regression > Random Forest Regressor > AdaBoost Regressor > Gradient Boosting Regressor > Decision Tree Regressor > KNeighbors Regressor**





