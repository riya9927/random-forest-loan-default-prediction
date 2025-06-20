# 🤖 Loan Default Prediction using Random Forest & Hyperparameter Tuning

This project aims to predict whether a borrower will repay a loan using a machine learning model. We use Decision Trees and Random Forests with Grid Search and Randomized Search to find the best hyperparameters for the model.

## 📊 Problem Statement

**Peerloankart** is a peer-to-peer lending NBFC. As an investor, you want to fund borrowers with a high probability of repayment. The goal is to create a model that predicts if a borrower is likely to **default**.

---

## 🧾 Dataset

The dataset contains 9,578 entries and includes the following features:

- `credit.policy`: Whether the customer meets the credit underwriting criteria.
- `fico`: Credit score.
- `purpose`: The purpose for the loan.
- `not.fully.paid`: Target variable (1 = defaulted, 0 = repaid).

## 🛠️ Technologies Used

- Python
- NumPy, Pandas
- Seaborn, Matplotlib
- Scikit-learn

---

## 🧠 Model Workflow

1. **Data Cleaning**
   - Handled null values and encoded categorical variables.
   
2. **Exploratory Data Analysis**
   - Visualizations of FICO scores, loan purposes, etc.

3. **Modeling**
   - Decision Tree Classifier
   - Random Forest Classifier

4. **Hyperparameter Tuning**
   - `GridSearchCV`
   - `RandomizedSearchCV`

5. **Evaluation Metrics**
   - Accuracy
   - Confusion Matrix
   - Feature Importance

---

## 🔍 Best Results

- **GridSearchCV Best Params**:  
  `max_depth=5`, `max_features=0.3`, `max_samples=0.8`, `n_estimators=50`
  
- **RandomizedSearchCV Best Params**:  
  `max_depth=8`, `max_features=1`, `max_samples=1`, `n_estimators=150`
  
- **Accuracy Achieved**: ~83%
