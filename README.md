# Task 6 – Linear Regression: House Price Prediction

## Objective
Build a Linear Regression model to predict house prices using the California Housing dataset and evaluate it using MAE and RMSE.

---

## Tools & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## Dataset
California Housing Dataset (from Scikit-learn):
- Features: 8 numerical input variables
- Target: MedHouseValue (continuous)

---

## Steps Performed
1. Loaded California housing dataset and converted into Pandas DataFrame
2. Performed basic inspection (.head, .info, .describe)
3. Split dataset into features (X) and target (y)
4. Train-test split (80-20)
5. Trained Linear Regression model
6. Predicted house prices on test set
7. Evaluated model using:
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
8. Created Predicted vs Actual scatter plot
9. Interpreted coefficients to identify most impactful features

---

## Model Evaluation
The notebook prints:
- MAE
- RMSE

---

## Final Outcome
Successfully built a regression model and understood:
- Train-test split importance
- Regression evaluation metrics
- Coefficient interpretation

---
