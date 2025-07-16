# 📊 Loan Approval Prediction

This project uses machine learning to predict whether a loan application will be **Approved** or **Rejected**, automating the process for banks and financial institutions.

---

## 🚀 Objective

- Automate the loan approval process using machine learning.
- Reduce manual errors, biases, and processing time.
- Ensure fairness and consistency in loan decisions.

---

## 📌 Project Workflow

### 1️⃣ Data Cleaning
- Removed spaces from column names and values.
- Standardized categorical columns (education, self_employed, etc.).
- Handled missing values via median/mode imputation.

### 2️⃣ Exploratory Data Analysis (EDA)
- Univariate analysis using KDE plots and countplots.
- Bivariate analysis using boxplots and barplots.
- Correlation heatmap to identify feature relationships.

### 3️⃣ Feature Engineering
- Label encoding of categorical variables.
- Standardized numerical features using `StandardScaler`.

### 4️⃣ Modeling
- Logistic Regression:
  - Model trained using scikit-learn.
  - Evaluated with accuracy score, ROC-AUC, confusion matrix, and classification report.

### 5️⃣ Feature Importance
- Plotted logistic regression coefficients.
- Interpreted positive and negative impacts on loan approval.

---

## 📊 Visualizations

- KDE & Countplots (Feature Distributions)
- Correlation Matrix Heatmap
- ROC Curve & AUC Score
- Feature Importance Bar Chart

---

## 📈 Results

- **Model Used:** Logistic Regression
- **Performance Metrics:**
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC Score

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 👨‍💻 Author

**Shekhar Mishra**

---

## 🚀 Getting Started

```bash
# Clone the repo
git clone <https://github.com/shekhar540/Loan-Approval-Prediction-Project>
