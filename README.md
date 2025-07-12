Aimerz Assignment House Rent Prediction Using Linear Regression

This project aims to build a predictive model that estimates house rent prices based on various features such as size, number of bedrooms, furnishing status, and location. The model is built using Linear Regression and follows a structured data science pipeline — from data cleaning to evaluation.

 Objective
To predict the monthly house rent based on the given features using Linear Regression, and understand the underlying patterns in the rental housing market.

Steps Followed
1. Data Loading & Initial Exploration
Loaded dataset using pandas

Inspected column types, missing values, and basic statistics

2. Exploratory Data Analysis (EDA)
Performed univariate and bivariate analysis

Visualized relationships using seaborn and plotly express

Observed correlation between numeric features and Rent

3. Data Preprocessing
Handled missing values

Encoded categorical variables using Label Encoding and One-Hot Encoding

Standardized/Normalized features as needed

4. Model Building
Split dataset into train and test sets (80:20)

Built a Linear Regression model using scikit-learn

Trained the model and predicted on the test set

5. Model Evaluation
Evaluated using metrics:

Mean Absolute Error (MAE): 0.35621511042416515

Root Mean Squared Error (RMSE): 0.6862171276623317

R² Score (Coefficient of Determination): 0.5291060537028591

6. Visualization
Compared actual vs predicted Rent using scatter plots

Plotted residual errors


Results

R² Score	
MAE	
RMSE

Technologies Used- 
Python
Pandas, NumPy
Seaborn, Matplotlib, Plotly Express
Scikit-learn
