
# Summary of Credit-Risk Classification Analysis

This analysis aimed to develop and evaluate a machine learning model to predict the credit risk of loans by classifying them into "healthy" or "high-risk" categories.

### Key Points:
- **Purpose**: Predict credit risk using a logistic regression model.
- **Dataset**: Included loan and financial information (e.g., income, debt).
- **Target Variable**: `loan_status` with two classes:
  - **0 (Healthy Loan)**: Low risk of default.
  - **1 (High-Risk Loan)**: High risk of default.

### Methodology:
1. **Data Preparation**: Split dataset into training and testing subsets.
2. **Model Training**: Trained a logistic regression model.
3. **Model Evaluation**: Evaluated using a confusion matrix and classification report.

### Results:
- **Class 0 (Healthy Loan)**:
  - **Precision**: 1.00
  - **Recall**: 1.00
  - **F1-Score**: 1.00
- **Class 1 (High-Risk Loan)**:
  - **Precision**: 0.87
  - **Recall**: 0.95
  - **F1-Score**: 0.91
- **Overall Accuracy**: 0.99

### Recommendations:
- **Best Performing Model**: Logistic regression with high accuracy and balanced performance.
- **Use Case**: Suitable for applications needing high recall for high-risk loans and overall reliable predictions.
- **Additional Models**: Not necessary, as the current model performs exceptionally well.

This model effectively distinguishes between healthy and high-risk loans, making it highly valuable for credit risk assessment.
