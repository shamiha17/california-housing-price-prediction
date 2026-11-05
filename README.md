# California Housing Price Prediction

## Project Overview

This project focuses on predicting median house values using the California Housing dataset.

The main goal is to build and compare three regression models: Ordinary Least Squares (OLS), Ridge Regression (L2), and Lasso Regression (L1).

The project also explores feature engineering, missing value imputation, and multicollinearity handling to improve model performance.

## Objectives

- Load and explore the California Housing dataset.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values using imputation techniques.
- Engineer interaction features.
- Analyze multicollinearity using correlation analysis and Variance Inflation Factor (VIF).
- Train OLS, Ridge, and Lasso regression models.
- Compare model performance using RMSE, MAE, and R².

## Dataset

**Dataset:** California Housing Dataset

The dataset contains information about housing districts in California.

**Target Variable:** Median House Value (`MedHouseVal`)

**Main Features:**
- MedInc
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

**Dataset Source:** [Scikit-learn California Housing Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Jupyter Notebook / Google Colab

## Project Workflow

### 1. Data Loading
Load the California Housing dataset and inspect its structure.

### 2. Exploratory Data Analysis (EDA)
- Check dataset shape and data types.
- Generate statistical summaries.
- Analyze missing values.
- Visualize feature distributions and correlations.

### 3. Data Preprocessing
- Handle missing values using imputation.
- Separate features and target variables.
- Split the dataset into training and testing sets.

### 4. Feature Engineering
Create interaction features to capture relationships between selected variables.

### 5. Multicollinearity Analysis
- Analyze feature correlations.
- Calculate Variance Inflation Factor (VIF).
- Handle highly correlated features where appropriate.

### 6. Feature Scaling
Apply feature scaling to prepare the data for regularized regression models.

### 7. Model Training
Train the following regression models:

- **Ordinary Least Squares (OLS):** A baseline linear regression model.
- **Ridge Regression (L2):** Uses L2 regularization to reduce the impact of large coefficients.
- **Lasso Regression (L1):** Uses L1 regularization and can shrink some coefficients to zero.

### 8. Model Evaluation
Compare the models using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score

## Model Comparison

The three regression models are evaluated using the same test dataset to ensure a fair comparison.

| Model | RMSE | MAE | R² Score |
|---|---|---|---|
| OLS | To be updated | To be updated | To be updated |
| Ridge | To be updated | To be updated | To be updated |
| Lasso | To be updated | To be updated | To be updated |

*Actual evaluation results will be added after executing the notebook.*

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/shamiha17/california-housing-price-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd california-housing-price-prediction
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `Task2_California_Housing_Regression.ipynb` and run all cells.

   Alternatively, upload the notebook to Google Colab.

## Repository Structure

```text
california-housing-price-prediction/
│
├── Task2_California_Housing_Regression.ipynb
├── README.md
└── requirements.txt
```

## Conclusion

This project demonstrates a complete regression workflow, including data preprocessing, feature engineering, multicollinearity analysis, model training, and evaluation.

By comparing OLS, Ridge, and Lasso regression, this project provides practical experience in understanding linear regression and regularization techniques.

## Author

**Shamiha Jahan**

GitHub: [shamiha17](https://github.com/shamiha17)

---

*This project was completed as part of the Datheon Machine Learning & Data Science Internship Task 2.*
