# Support-vector-regression
This project explores the Tips dataset from the Seaborn library, focusing on data preprocessing, exploratory data analysis, and modeling using Support Vector Regression (SVR). Key techniques implemented include one-hot encoding and label encoding for categorical features, along with hyperparameter tuning using Grid Search CV to optimize the SVR model's performance. The project demonstrates the relationship between total bills and tips, providing insights and visualizations to understand the data better.

# Tips Data Analysis and Support Vector Regression

## Project Overview

This project utilizes the **Tips** dataset from the **Seaborn** library to perform exploratory data analysis and build a Support Vector Regression (SVR) model. The dataset contains information about restaurant tips, including various features such as total bill, tip amount, gender, day, and time.

## Key Features

- **Data Preprocessing**: 
  - One-Hot Encoding: Categorical variables are transformed into a format suitable for machine learning algorithms.
  - Label Encoding: Some categorical features are label encoded for modeling.

- **Exploratory Data Analysis (EDA)**: 
  - Visualization of relationships between features and target variables.

- **Modeling**: 
  - Support Vector Regression (SVR) is used to predict the tip amount based on the features.
  - Hyperparameter tuning is performed using **Grid Search CV** to optimize model performance.

## Requirements

To run this project, you need the following libraries:

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install the required libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
