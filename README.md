# **Handling imbalanced data**

## 📊 Handling Imbalanced Data in Customer Churn Prediction using ANN

This project tackles the class imbalance problem in customer churn datasets by applying four different data balancing techniques and training an Artificial Neural Network (ANN) on each. The project is implemented in Google Colab, making it easy to run without any setup.

---

## 🎯 Objective

To build and compare the performance of ANN models trained on:

- 🔁 Random Oversampling  
- 🔻 Random Undersampling  
- 🔄 SMOTE (Synthetic Minority Over-sampling Technique)  
- 🧠 Ensemble Method

---

## 🧠 Model Used

**Artificial Neural Network (ANN)**  
Trained using each data balancing method to evaluate its effect on churn prediction performance.

---

## ⚙️ Technologies & Libraries

- Python (Google Colab)  
- Pandas, NumPy  
- scikit-learn  
- imbalanced-learn  
- TensorFlow / Keras  
- Matplotlib, Seaborn  

---

## 📂 Dataset Description

The dataset includes:

- 👤 Customer demographics  
- 📶 Service usage  
- 💳 Contract/billing details  
- 🎯 Target variable: `Churn (Yes/No)`

---

## 🔄 Data Handling Techniques

| Technique              | Description                                             |
|------------------------|---------------------------------------------------------|
| Random Oversampling    | Duplicates samples from the minority class              |
| Random Undersampling   | Removes samples from the majority class                 |
| SMOTE                  | Generates synthetic examples of the minority class      |
| Ensemble Method        | Combines models trained on different balanced datasets  |

---

## 🔬 Project Workflow

- Data Exploration & Preprocessing  
- Apply 4 Balancing Techniques  
- Train ANN on each balanced dataset  
- Model Evaluation using:  
  - Confusion Matrix  
  - Classification Report  
  - Accuracy, Precision, Recall, F1-Score  

---

## 📈 Results & Insights

- Imbalanced data resulted in biased predictions favoring non-churners.  
- Balancing techniques, especially SMOTE and Ensemble, improved the ANN’s ability to predict churners.  
- The ensemble method produced the most stable and accurate results.

---

## 🚀 Run in Google Colab

Click the button below to run this notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tashfeen786/Handling-imbalanced-data-/blob/main/Handling_imbalanced_data_in_customer_churn_prediction.ipynb)

---

## 📁 Repository Structure

📦Handling-imbalanced-data-
┣ 📜 Handling_imbalanced_data_in_customer_churn_prediction.ipynb
┗ 📄 README.md


---

## 🙋‍♂️ Author

**Tashfeen Aziz**  
Data Analyst | Python Developer | ML/DL Enthusiast  
🔗 [GitHub](https://github.com/tashfeen786) | [LinkedIn](https://www.linkedin.com/in/tashfeenaziz/)

---

## ⭐️ Show Some Love

If you found this helpful, don’t forget to **Star ⭐ the repo**, fork it, or share it with others!
