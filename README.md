# 📈 Predicting Bank Term Deposit Subscription

## 🧠 Project Overview

This project was developed as part of a **hackathon challenge**, where the goal was to **predict whether a client will subscribe to a term deposit** based on historical marketing campaign data. Using classification techniques, we aimed to build a robust predictive model to help banks optimize their outreach and marketing strategies.

---

## 📊 Dataset Description

The dataset contains **41,188 rows and 21 columns**, representing client and campaign-related attributes. The **target variable** is `y`, indicating whether the client subscribed to a term deposit (`yes` or `no`).

### Key Features:

- **Client Profile:** `age`, `job`, `marital`, `education`, `default`, `housing`, `loan`
- **Campaign Contact Info:** `contact`, `month`, `day_of_week`, `campaign`, `pdays`, `previous`, `poutcome`
- **Economic Indicators:** `emp.var.rate`, `cons.price.idx`, `cons.conf.idx`, `euribor3m`, `nr.employed`

---

## 🔍 Objective

- **Binary Classification Problem:** Predict if a client (`y`) will subscribe to a term deposit using machine learning models.
- **Business Impact:** Helps banks improve marketing targeting, reduce outreach costs, and enhance conversion rates.

---

## 🛠️ Tools & Technologies Used

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Models Tried:** Logistic Regression, Decision Trees, Random Forest, XGBoost  
- **Metrics Used:** Accuracy, Precision, Recall, F1-Score, ROC-AUC  

---

## 🚀 Approach

1. **Data Preprocessing**
   - Handled categorical variables with one-hot encoding
   - Managed missing values (e.g., `unknown`)
   - Scaled numerical features where appropriate

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions
   - Identified correlations and class imbalances

3. **Model Training & Evaluation**
   - Trained multiple classification models
   - Performed cross-validation for robustness
   - Evaluated models using confusion matrix and AUC scores

4. **Feature Importance**
   - Analyzed feature contributions using tree-based models

---

## ✅ Results

- Achieved **X% accuracy** and **Y AUC score** on the validation set *(fill in after results)*  
- Found that features like `poutcome`, `euribor3m`, and `nr.employed` were key predictors

---

## 📦 How to Run

1. Clone the repo  
```bash
git clone https://github.com/yourusername/bank-term-deposit-prediction.git
cd bank-term-deposit-prediction
```

2. Install dependencies  
```bash
pip install -r requirements.txt
```

3. Run the notebook or script  
```bash
jupyter notebook bank_marketing_prediction.ipynb
```

---

## 📚 References

- Dataset Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Scikit-learn Documentation
- Kaggle & GitHub community solutions for benchmarking

---

## 🤝 Team

This project was developed during a hackathon by [Your Name] and collaborators.

---

Let me know if you'd like to add visualizations, model evaluation metrics, or GitHub deployment tips to this readme!
