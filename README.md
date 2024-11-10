# Medical Insurance Cost Prediction

This project predicts medical insurance costs based on demographic and lifestyle factors using regression models. It highlights the impact of features like age, BMI, smoking status, and region on insurance costs.

## Overview
Medical insurance costs are influenced by various factors, such as age, BMI, smoking status, and the number of dependents. This project builds predictive models to estimate costs based on these features.

## Dataset
The dataset, available on [Kaggle](https://www.kaggle.com/mirichoi0218/insurance), includes:
- **age, sex, bmi, children, smoker, region**: Features influencing medical costs.
- **charges**: Target variable, representing insurance costs.

## Requirements
Install the necessary libraries with:
```bash
pip install -r requirements.txt
```

## Project Structure
- **`Medical_Insurance_Cost_Prediction.ipynb`**: Jupyter notebook containing all code, EDA, and modeling steps.
- **`insurance.csv`**: Dataset file (not included, please add your own).
- **`README.md`**: Project summary and instructions.

## Notebook Outline
The notebook follows these steps:
1. **Data Loading and EDA**: Overview and visualizations of the data.
2. **Data Preprocessing**: One-hot encoding for categorical variables.
3. **Modeling**: Training and evaluating three models:
   - **Linear Regression**
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
4. **Evaluation**: Models evaluated with Mean Absolute Error (MAE) and Mean Squared Error (MSE).


## Conclusion
The Gradient Boosting model showed the best performance, with the lowest error values. Further improvements, such as hyperparameter tuning and feature engineering, could further enhance accuracy.
