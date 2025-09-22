# Medical-Expense-Detector

A machine learning project that predicts medical expenses based on demographic and health-related attributes such as age, BMI, smoking habits, and dependents.

## Tech Stack
- Python  
- scikit-learn  
- pandas, numpy  
- matplotlib, seaborn  

## Dataset
The dataset was sourced from [Medical Charges Dataset](https://raw.githubusercontent.com/JovianML/opendatasets/master/data/medical-charges.csv).  
It contains information on patients’ demographics, lifestyle, and their medical charges.

## Methodology
1. Data preprocessing (handling categorical data, feature encoding, normalization).  
2. Exploratory Data Analysis (EDA) to identify correlations and key cost drivers.  
3. Regression modeling with scikit-learn (Linear Regression, etc.).  
4. Model evaluation using RMSE (Root Mean Squared Error).  

## Results
- Predicted medical expenses with reasonable accuracy.  
- Identified **age, BMI, and smoking status** as major cost drivers.  

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/medical-expense-detector.git
   cd medical-expense-detector

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Open and run the Jupyter/Colab notebook:
   ```bash
   jupyter notebook Predicting_Medical_Expenses.ipynb
