# 🏡 APR_ASSIGNMENT1_LOR  
_Logistic Regression Model for Housing Price Prediction_  

---

## 📌 Overview  
This project demonstrates the process of building a **Logistic Regression** model to predict whether a house price is **above or below the median price**, using the provided `data.csv` dataset.  

The notebook covers:  
- Data loading  
- Preprocessing  
- Model training  
- Evaluation  
- Visualization  

---

## 🔎 Project Steps  

### 1. Data Loading  
- The dataset (`data.csv`) was loaded into a pandas DataFrame.  

### 2. Data Preprocessing  
- Removed irrelevant columns:  
  - `date`, `street`, `city`, `statezip`, `country`  
- Created a **binary target variable** `price_binary`:  
  - `1` → Price above the median  
  - `0` → Price below the median  
- Scaled numerical features using **StandardScaler**.  
- Split data into:  
  - **Training set** → 80%  
  - **Testing set** → 20%  

### 3. Model Training  
- Trained a **Logistic Regression model** on the preprocessed training data.  

### 4. Model Evaluation  
- Evaluated the trained model on the **test set**.  

### 5. Data Visualization  
- Generated a **box plot** to visualize the relationship between the number of floors and the binary price.  

---

## 📈 Results  

### 🔹 Model Performance Metrics  
- **Accuracy:** 76.09%  
- **Precision:** 76.14%  
- **Recall:** 74.44%  
- **F1-score:** 75.28%  

### 🔹 Data Analysis Insights  
- The **box plot** suggested potential differences in house prices based on the number of floors.  
- This indicates that `floors` might be a relevant feature for predicting house prices.  

---

## 🚀 Next Steps  
- Perform **feature engineering** and **hyperparameter tuning** to improve model accuracy.  
- Explore additional models (e.g., Random Forest, Gradient Boosting).  
- Investigate the statistical significance of the relationship between `floors` and `price_binary`.  
- Add more detailed **visualizations** and **statistical tests** for deeper insights.  

---

📂 **Deliverables**:  
- Jupyter Notebook (`.ipynb`)  
- Dataset (`data.csv`)  
- README.md (this file)  

---
