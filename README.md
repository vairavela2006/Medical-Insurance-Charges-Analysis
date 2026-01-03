# 🩺 Medical Insurance Charges – Data Analytics & Regression

## 📌 Project Overview
This project performs data analytics and predictive modeling on a medical insurance dataset to understand the key factors influencing insurance charges and to build regression models for accurate charge prediction.

The dataset is a modified version of the Medical Insurance Price Prediction dataset available on Kaggle under the CC0 1.0 Universal License.

---

## 🎯 Objectives
- Load and clean medical insurance data
- Perform Exploratory Data Analysis (EDA)
- Identify features affecting insurance charges
- Build Single-variable Linear Regression models
- Build Multi-variable Linear Regression models
- Improve performance using Ridge Regression

---

## 📊 Dataset Description

| Feature | Description |
|------|------------|
| Age | Age of the insured |
| Gender | Female = 1, Male = 2 |
| BMI | Body Mass Index |
| No_of_Children | Number of children |
| Smoker | Smoker = 1, Non-smoker = 2 |
| Region | NW=1, NE=2, SW=3, SE=4 |
| Charges | Insurance charges (USD) |

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis
Key insights from EDA:
- Smoking status has the strongest impact on insurance charges
- BMI and Age show positive correlation with charges
- Gender and Region have minimal influence

---

## 🤖 Model Building
### Models Implemented
- Single Variable Linear Regression
- Multi Variable Linear Regression
- Ridge Regression (Regularized Linear Model)

### Performance
- Multi-variable regression significantly improves accuracy
- Ridge regression reduces overfitting and improves generalization

---

## 📌 Conclusion
The project demonstrates how data analytics and regression techniques can be used to analyze medical insurance costs and build effective predictive models. Ridge regression provides more stable predictions compared to standard linear regression.

---

## 🚀 Future Enhancements
- Try Lasso and ElasticNet regression
- Implement Random Forest and XGBoost
- Deploy the model using Flask or Streamlit

---

## 📂 How to Run
```bash
pip install -r requirements.txt
jupyter notebook
