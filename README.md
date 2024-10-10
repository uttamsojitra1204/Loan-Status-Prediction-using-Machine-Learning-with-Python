# Loan-Status-Prediction-using-Machine-Learning-with-Python

This project aims to build a machine learning model to predict whether a loan applicant is eligible for a loan based on their personal and financial details. The dataset used for training the model contains information about various applicants such as gender, marital status, income, loan amount, and credit history.

=> Workflow

1. Data Preprocessing:
- Checked for missing values and dropped rows with missing data.
- Label encoding was performed to convert categorical columns (like Gender, Education, Loan_Status) into numerical values.
- Feature engineering was applied to transform dependent variables and prepare the dataset for training.

2. Exploratory Data Analysis:
- Visualized the relationship between education, marital status, credit history, and loan status using seaborn's countplot.

3. Model Training:
- Split the dataset into training and test sets using an 80/20 split.
- Trained a Support Vector Machine (SVM) classifier with a linear kernel to predict loan eligibility.

4. Model Evaluation:
- Evaluated the model on both training and test sets using accuracy score.
- Achieved 80.32% accuracy on training data and 79.17% accuracy on test data.

5. Prediction:
- A function was created to input an applicant's details and predict their loan eligibility. If the prediction is 1, the applicant is eligible for a loan; otherwise, they are not eligible.

=> Coclusion
- This project involves building a Loan Eligibility Prediction System using machine learning. We processed a dataset with features like income, loan amount, credit history, and more to predict loan eligibility. After handling missing values and encoding categorical data, we used a Support Vector Machine (SVM) model for classification. The model achieved 80.3% accuracy on the training set and 79.2% accuracy on the test set, showing its effectiveness in predicting loan approval. The system provides valuable insights for financial institutions in streamlining the loan approval process.
