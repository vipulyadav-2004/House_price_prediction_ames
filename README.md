# 🏠 House Price Prediction - Ames Housing Dataset

This project uses advanced regression techniques to predict house prices with **91% accuracy**. I performed the full data science lifecycle: from messy data cleaning to building a high-performance Random Forest model.

## 🚀 Key Highlights
* **Cleaning:** Handled 2,900+ missing values across 79 features (dropping irrelevant ones like `PoolQC` and imputing others).
* **Feature Engineering:** Created new powerful features like `TotalSF` (Total Square Footage) and `HouseAge`.
* **Preprocessing:** Applied Log-Transformation to the target variable to handle right-skewness and used One-Hot Encoding for categorical data.
* **Modeling:** Compared Linear Regression against Random Forest Regressor.

## 📈 Results
| Model | R-squared Score |
| :--- | :--- |
| **Linear Regression** | 0.8952 |
| **Random Forest** | **0.9127** |

<img width="751" height="478" alt="image" src="https://github.com/user-attachments/assets/aa1ad6af-e66d-4582-9de2-3cadc0873ea9" />


The Random Forest model captures non-linear relationships better, resulting in more accurate predictions for high-value homes.
