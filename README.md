
# Heart Disease Prediction

A **Machine Learning** application for predicting the likelihood of heart disease based on patient details, using **Logistic Regression**. This project uses the **Heart Disease Dataset** and is built with **Python** and **Streamlit** for an interactive frontend.

---

## 🚀 Project Overview

This project predicts the presence of heart disease in a patient based on various health-related factors such as age, blood pressure, cholesterol levels, etc. A **Logistic Regression** model is used for prediction. The user enters the details through the Streamlit interface, and the model predicts the likelihood of heart disease.

---

## 🖼️ Screenshots

### 📌 User Input Form & Prediction Outcome
The user inputs various health details to predict the risk of heart disease & Displays the prediction based on the entered details.

![Heart Disease Input Form](./screenshots/heart_disease_img.png)

---

## 📁 Project Structure

```
📦 Heart-Disease-Prediction
│
├── app.py                     → Streamlit app for the frontend
├── Heart_Disease_Predictor.ipynb → Jupyter notebook for model building and evaluation
├── heart_disease_model.pkl     → Trained Logistic Regression model
│
├── heart_disease_img.png
│
├── heart.csv               → Dataset containing patient health details
└── README.md                   → Project documentation
```

---

## 📊 Data Used

The **Heart Disease Dataset** contains the following columns:

- **Age**: Age of the patient
- **Sex**: Gender of the patient
- **Chest Pain Type**: Type of chest pain (4 categories)
- **Resting Blood Pressure**: Blood pressure while resting
- **Cholesterol**: Serum cholesterol level
- **Fasting Blood Sugar**: Fasting blood sugar level (> 120 mg/dl or not)
- **Resting Electrocardiographic Results**: Results of resting ECG
- **Max Heart Rate**: Maximum heart rate achieved
- **Exercise Induced Angina**: Whether exercise-induced angina is present
- **Oldpeak**: Depression induced by exercise relative to rest
- **Slope**: Slope of the peak exercise ST segment
- **Major Vessels**: Number of major vessels colored by fluoroscopy
- **Thalassemia**: Thalassemia defect
- **Target**: 1 if heart disease is present, 0 otherwise

---

## 🧠 How the Model Works

The heart disease prediction model uses **Logistic Regression** to classify whether a patient is at risk of heart disease or not.

### Model Workflow:
1. **Data Preprocessing**: The dataset is loaded and divided into features (X) and target (y).
2. **Model Training**: The model is trained using `LogisticRegression` from **sklearn**.
3. **Prediction**: After training, the model predicts the target variable (heart disease presence).
4. **Evaluation**: The model's accuracy is evaluated using the training dataset.

### Training Accuracy:
After training the model, the accuracy score on the training data is approximately **85%**.

---

## ▶️ How to Run the Project

### **1. Clone the repository**
```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### **2. Install dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Streamlit app**
```bash
streamlit run app.py
```

### **4. Open in browser**
```
http://localhost:8501/
```

---

## 🔮 Future Enhancements

- Improve model performance by experimenting with other algorithms such as **Random Forest** or **XGBoost**.
- Add personalized health insights based on predictions.
- Implement user authentication and save prediction history.
- Deploy the app online using **Streamlit Cloud** or **Heroku**.

---

## 📄 License
This project is licensed under the shivamsahu2001 License.

---
