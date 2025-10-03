# wine-quality-ml

#  Wine Quality Prediction (Machine Learning Project)

This project applies machine learning to predict the quality of red wine based on its physicochemical properties. The dataset is taken from the UCI Machine Learning Repository and contains 1,599 samples of Portuguese *Vinho Verde* red wine.

---

##  Project Overview
- Performed **exploratory data analysis (EDA)** to examine distributions, correlations, and feature relationships.  
- Preprocessed the dataset (handled outliers, scaling, validated regression suitability).  
- Implemented **Linear Regression** and **Decision Tree Regressor** models using scikit-learn.  
- Compared models based on accuracy and interpretability.  
  
## 📈 Results
- **Linear Regression**: Performed best on the dataset, capturing overall trends.  
- **Decision Tree**: Lower accuracy but provided more interpretability.  
- **Note:** This project was originally assessed as coursework and graded **95% (First Class)**.  

---

## 🗂️ Dataset
- **Source:** [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)  
- **Samples:** 1,599 red wines  
- **Features:** 11 physicochemical properties (e.g., acidity, sulphates, alcohol content)  
- **Target:** Wine quality (score 0–10)  

---

## ⚙️ Tech Stack
- **Language:** Python (Jupyter Notebook)  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/sreyas-sreekumar/wine-quality-ml.git
   cd wine-quality-ml
