# Heart Disease Prediction

Predicts the presence of heart disease using patient clinical data and logistic regression.

## Dataset
UCI Heart Disease Dataset — 303 patient records, 13 clinical features (age, cholesterol, chest pain type, max heart rate, etc.)

## What This Project Does
- Cleans and prepares the dataset (missing value checks, duplicate removal, target encoding)
- Explores key relationships between patient features and heart disease outcomes
- Builds a logistic regression classifier with standardized features
- Evaluates the model using accuracy, ROC-AUC, confusion matrix, and a classification report
- Visualizes the strongest predictors via logistic regression coefficients

## Results
| Metric | Score |
|--------|-------|
| Accuracy | 78.69% |
| ROC-AUC | 0.8647 |

## Tools
Python, pandas, NumPy, scikit-learn, matplotlib, Jupyter Notebook

## How to Run
```bash
jupyter notebook heart_disease_prediction.ipynb
```
Run all cells top to bottom. The notebook will download the dataset automatically.
