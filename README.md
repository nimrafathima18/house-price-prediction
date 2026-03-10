# house-price-prediction


## Project Overview
The goal of this project is to build a machine learning model that predicts house prices based on different features of a house, such as area, quality, number of rooms, and construction year. Accurate house price prediction helps buyers, sellers, and real estate companies make informed decisions.

This project demonstrates the complete data science workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, and model evaluation.

---

## Dataset
The dataset used in this project contains detailed information about houses and their sale prices.

Some important features in the dataset include:

- **GrLivArea** – Above-ground living area (square feet)
- **OverallQual** – Overall quality of the house
- **YearBuilt** – Year the house was built
- **TotalBsmtSF** – Basement area
- **FullBath** – Number of full bathrooms
- **BedroomAbvGr** – Number of bedrooms above ground
- **SalePrice** – Target variable (house price)

The dataset was cleaned and prepared before building the model.

---

## Data Preprocessing
Several preprocessing steps were performed to prepare the dataset for machine learning:

- Handling missing values
- Removing duplicate records
- Detecting and removing outliers using the **IQR method**
- Encoding categorical variables
- Feature scaling for regression models

---

## Exploratory Data Analysis (EDA)
EDA was performed to understand the relationships between house features and the sale price.

Some visualizations used:

- Distribution plot of **SalePrice**
- Scatter plot of **Living Area vs SalePrice**
- Box plot of **Overall Quality vs SalePrice**
- Correlation heatmap to identify the most important features

Key insight:

Houses with larger living areas and higher overall quality tend to have higher sale prices.

---

## Feature Engineering
New features were created to improve model performance.

Examples:

- **TotalArea** = Basement Area + 1st Floor Area + 2nd Floor Area
- **TotalBathrooms** combining full and half bathrooms

Feature engineering helps the model capture better patterns in the data.

---

## Machine Learning Models
Multiple regression models were trained and compared:

1. Linear Regression
2. Ridge Regression
3. Lasso Regression
4. Random Forest Regressor

Training multiple models helps identify the best-performing model for the dataset.

---

## Model Evaluation
The models were evaluated using the following metrics:

- **RMSE (Root Mean Squared Error)**  
Measures the average prediction error.

- **MAE (Mean Absolute Error)**  
Measures the average absolute difference between predicted and actual prices.

- **R² Score**  
Indicates how well the model explains the variance in house prices.

Random Forest performed the best among the tested models.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

## Project Workflow

1. Data Collection  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation

---

## Conclusion
This project demonstrates how machine learning can be applied to predict house prices using real-world data. By applying data preprocessing, feature engineering, and multiple regression models, we can build a predictive model that provides useful insights for the real estate market.

---

## Author
Fathima
