# Loan Approval Prediction using Logistic Regression

## Objective
#The objective of this project is to build a Logistic Regression model to predict whether a loan application will be approved or rejected based on applicant details.

-------------------------------------------------------------------------------------------

## Dataset Description

The dataset contains 200 records with the following features:

- Gender
- Age
- Income
- Loan Amount
- Credit Score
- Employment Status
- Marital Status
- Loan Approved (Target Variable)

-------------------------------------------------------------------------------------------

## Project Workflow

The following steps were performed:

1. Data loading using pandas
2. Exploratory Data Analysis (EDA)
3. Handling categorical variables using encoding
4. Feature scaling using StandardScaler
5. Train-test split (80–20)
6. Logistic Regression model training
7. Model evaluation using:
   - Accuracy
   - Recall
   - Precision
   - Confusion Matrix
8. Prediction on new user input data

-------------------------------------------------------------------------------------------

## Model Performance

Accuracy: 87.5%

The model performs well in predicting loan approval status using applicant financial and demographic details.

-------------------------------------------------------------------------------------------

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

-------------------------------------------------------------------------------------------


## Project Structure

loan-approval-logistic-regression/
│
├── loan_approval_model.ipynb
├── loan.csv
├── README.md
├── requirements.txt
└── loan_model.pkl

-------------------------------------------------------------------------------------------

## Future Improvements

- Try Decision Tree and Random Forest
- Perform hyperparameter tuning
- Deploy model using Streamlit
- Add cross-validation

-------------------------------------------------------------------------------------------

## Author

Jessica Suri
Aspiring Data Scientist | AI Engineer