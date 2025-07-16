# Wheat-Yield-and-Climate-Data-Analysis-Project


## Project Overview  
This project explores the relationship between wheat yield and climate factors (temperature and precipitation) across selected European countries (France, Germany, Italy, Poland, Spain) from 2020 to 2022. The goal is to analyze data patterns, build predictive models, and interpret the influence of climate on crop yield.

## Data Sources  
- **Wheat Yield Data:** Official statistics from FAOSTAT.  
- **Climate Data:** Temperature (°C) and precipitation (mm) records for the same countries and years.

## Data Preparation  
- Imported and merged datasets based on `Country` and `Year`.  
- Cleaned and explored data for missing values and consistency.  
- Selected relevant numerical features for modeling.

## Exploratory Data Analysis (EDA)  
- Examined dataset shape, data types, and sample rows.  
- Generated summary statistics for numerical variables.  
- Visualized distributions and trends using boxplots and line charts.  
- Computed and visualized correlations, revealing relationships among variables.

## Machine Learning Modeling  
- Split data into training (80%) and testing (20%) sets.  
- Scaled features using standardization.  
- Trained multiple regression models: Linear Regression, Decision Tree, and Random Forest.  
- Performed hyperparameter tuning with GridSearchCV on Random Forest for optimized performance.

## Model Evaluation  
- Evaluated models using Mean Squared Error (MSE) and R-squared (R²) metrics.  
- Compared model predictions visually against actual yields.  
- Noted that optimized Random Forest provided the best results, though further improvements are possible.

## Insights and Conclusions  
- Climate factors have measurable but complex effects on wheat yield.  
- Negative correlation observed between temperature and precipitation in the dataset.  
- Ensemble methods like Random Forest better capture nonlinearities than linear models.  



