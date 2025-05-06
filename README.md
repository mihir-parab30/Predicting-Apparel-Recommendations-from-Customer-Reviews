# 👗 Predicting Apparel Recommendations from Customer Reviews

## 🧠 Abstract
This project focuses on analyzing customer reviews from a fashion e-commerce dataset to predict whether a customer would recommend a product. The workflow begins with data cleaning, including handling missing values and duplicate records. Key features such as review text, ratings, and customer demographics are preprocessed and fed into various supervised machine learning models. Five classification models—Logistic Regression, Random Forest, XGBoost, Support Vector Machine, and Neural Network (MLPClassifier)—are trained and evaluated on their ability to handle imbalanced classes where non-recommendations are underrepresented. Performance is assessed using accuracy, F1-score, recall, and confusion matrices. Among all models, Logistic Regression emerged as the best-performing model with an accuracy of 89% and a balanced F1-score, while SVM showed the highest recall for dissatisfied customers. The project demonstrates how machine learning can be used to uncover insights from textual reviews and ratings to drive product improvements and customer satisfaction strategies in the fashion retail domain.

---

## 🎯 Business Problem
Fashion retailers struggle to understand what makes customers recommend or not recommend products. This project helps answer:
- What features indicate a customer is likely to recommend a product?
- Can we flag products with negative sentiment early?

---

## 💡 Technologies Used
- Python (Pandas, NumPy)
- Scikit-learn: Logistic Regression, Random Forest, SVM, MLPClassifier
- XGBoost
- Matplotlib, Seaborn
- Google Colab

---

## 📂 Data Source
[Womens Clothing E-Commerce Reviews Dataset (Kaggle)](https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews)

---

## ✨ Project Features
- Cleaned and preprocessed review and demographic data
- Handled missing values in textual and categorical features
- Identified and addressed class imbalance in labels
- Trained five machine learning models to predict recommendation likelihood
- Evaluated models using accuracy, recall, precision, and F1-score
- Visualized confusion matrices and performance reports
- Selected best-performing model (Logistic Regression); highlighted SVM as strong alternative

---

## 📊 Project Preview

### 🔹 Confusion Matrix – Logistic Regression
![Logistic CM](Screenshot_Logistic_CM.png)

### 🔹 Confusion Matrix – SVM
![SVM CM](Screenshot_SVM_CM.png)

---

## 🚀 How to Run

1. Open the notebook in Google Colab.
2. Upload the dataset file when prompted.
3. Run each cell sequentially to preprocess data, train models, and evaluate results.
4. The notebook includes performance summaries and visualizations.

---

## 🧠 Results & Conclusion

- **Best Model:** Logistic Regression  
  Achieved the highest overall balance of precision and recall across both classes with an accuracy of 89% and F1-score of 0.88.
  
- **Alternate Model:** Support Vector Machine  
  Performed best on Class 0 (non-recommenders), ideal for customer dissatisfaction detection.

- **Recommendation:** Use Logistic Regression for balanced classification and interpretability; consider SVM when focus is on early dissatisfaction alerts.

---

## 🧰 Key Skills Demonstrated

- Machine Learning Model Selection
- Text Data Preprocessing
- Class Imbalance Handling
- Model Evaluation & Confusion Matrix Analysis
- Python for Data Science
