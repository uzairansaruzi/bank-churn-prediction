# bank-churn-prediction
This project predicts customer churn in the banking sector using a Kaggle dataset. The analysis includes logistic regression and classification tree models. Insights are generated using the DIDA framework (Data, Insights, Decisions, and Advantage) to provide actionable recommendations for customer retention strategies.

# Bank Churn Prediction
This project predicts customer churn in the banking sector using machine learning models, including logistic regression and classification trees.

## Dataset
- Source: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn?resource=download)
- 10,000 observations with 18 variables, including customer demographics and account details.

## Methods
- **Logistic Regression (v1 and v2)**:
  - v1: Baseline model, dominated by 'Complain' predictor.
  - v2: Refined by excluding 'Complain' to explore other predictors.
- **Classification Tree**:
  - Captures non-linear interactions and provides decision rules.

## Key Metrics
- Logistic Regression (v2): Accuracy: 84%, AUC: 0.85
- Classification Tree: Depth: 6, AUC: 0.85

## Insights and Recommendations
- Address customer complaints proactively.
- Focus on inactive customers and regions with high churn rates (e.g., Germany).
- Simplify product offerings for customers with multiple products.

## Project Structure
- `data/`: Dataset file.
- `notebooks/`: Jupyter notebooks for model development.
- `reports/`: Proposal and final report.
- `README.md`: Project overview and instructions.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open the notebooks to explore the analysis and results.
