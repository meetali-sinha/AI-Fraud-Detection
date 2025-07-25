# 🚗 Auto Insurance Fraud Detection

Leveraging Machine Learning to Identify Fraudulent Claims and Reduce Insurance Losses

---

## 📌 Project Overview

Auto insurance fraud poses a significant challenge, leading to billions in losses and rising premiums. This project aims to develop a robust machine learning model to **detect fraudulent insurance claims**, ensuring claim integrity and minimizing financial risks.

---

## 📂 Project Structure

---

## 🧠 Methodology

### 1. **Data Understanding & Cleaning**
- Standardized column names.
- Removed duplicates.
- Filled missing values (e.g., `'Police_Report'`, `'authorities_contacted'`).
- Addressed missing categorical fields with custom values.

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed fraud distribution (class imbalance).
- Identified key features such as `Accident_Type`, `Accident_Severity`, and claim amount trends.
- Explored geographic and temporal fraud trends.

### 3. **Feature Engineering**
- Extracted date-based features: `Claim_Lag_Days`, `Vehicle_Age`, etc.
- Created claim-related ratios: `Injury_Claim_Ratio`, `Vehicle_Claim_Ratio`.
- Encoded categorical features using One-Hot Encoding.
- Scaled numerical data with `StandardScaler`.

### 4. **Modeling**
- Handled class imbalance with **SMOTE** (Synthetic Minority Over-sampling).
- Used **XGBoost Classifier** for robust prediction.
- Evaluated on precision, recall, F1-score, and ROC AUC.

---

## 📈 Results

| Metric         | Score      |
|----------------|------------|
| Precision      | *Your Score* |
| Recall         | *Your Score* |
| F1-Score       | *Your Score* |
| ROC AUC Score  | *Your Score* |

> ✅ The model showed strong performance in identifying fraudulent claims, especially after applying SMOTE to handle imbalance.

---

## 📊 Visualizations

- Confusion Matrix
- ROC Curve
- Class Distribution
- Feature Importance Plots

*(Find them in the `/images` folder)*

---

## 🚀 Future Work

- Tune model hyperparameters.
- Explore interpretable ML (e.g., SHAP, LIME).
- Real-time fraud detection deployment.
- Cost analysis: financial value of correctly flagged fraud.

---

## 💻 Tech Stack

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Imblearn, XGBoost
- **Tools**: Jupyter Notebook, Git, GitHub

---

## 🛠️ Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/auto-insurance-fraud-detection.git
   cd auto-insurance-fraud-detection


---

Let me know if you want me to generate the `requirements.txt` file content as well.

