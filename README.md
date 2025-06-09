# 🛡️ Credit Card Fraud Detection

This project detects fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, so emphasis is placed on recall and reducing false negatives. The project is implemented using Python and scikit-learn, and runs entirely on **Google Colab**.

---

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Records: 284,807 transactions
- Fraud Cases: 492 (~0.17%)
- Features: 30 anonymized columns (V1–V28, Time, Amount, Class)

---

## 🔧 Technologies Used

- Python
- NumPy & Pandas
- Scikit-learn
- Imbalanced-learn (optional)
- Google Colab

---

## 🧠 Model Used

- **Logistic Regression**  
  Used for binary classification to predict fraud. Evaluated using metrics suitable for imbalanced data.

---

## 🛠️ Project Workflow

1. **Data Loading**
   - Uploaded via Colab or loaded from Google Drive

2. **Preprocessing**
   - Feature scaling (if required)
   - Train-test split with stratification
   - Class imbalance handled using class weights or SMOTE

3. **Model Training**
   - Logistic Regression with `class_weight='balanced'`

4. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix and ROC-AUC

---

## 🚀 Run in Google Colab

Click the badge below to open and run the project in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VSBYbBJtWUKmmtb8ESKTe1AAyaBXlrgs?usp=sharing)

---

## ✅ Results

- **High recall** to minimize undetected fraud
- Good baseline accuracy
- Provides a foundation for more advanced models like XGBoost

---

## 📌 Future Improvements

- Try ensemble models (Random Forest, XGBoost)
- Use SMOTE/ADASYN for better balance
- Deploy using Flask/Streamlit or integrate with real-time data

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

> ⚠️ **Note**: This is an educational project and not ready for production use without further testing and validation.
