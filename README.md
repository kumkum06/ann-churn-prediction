# 📊 Customer Churn Prediction Using ANN

## 📌 Project Overview
This project predicts whether a customer is likely to leave a bank using an Artificial Neural Network (ANN). It uses customer information and a trained deep learning model to generate churn predictions.

The project includes data preprocessing, feature encoding, feature scaling, model training, and a Streamlit web application for predictions.

## 🎯 Objectives
- Predict customer churn using an Artificial Neural Network.
- Process customer data using encoding and feature scaling.
- Use a trained deep learning model to generate predictions.
- Provide an interactive interface using Streamlit.

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Artificial Neural Network (ANN)
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Jupyter Notebook

## 📂 Project Structure

```text
ANN/
├── app.py
├── Churn_Modelling.csv
├── experiments.ipynb
├── prediction.ipynb
├── model.h5
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── scaler.pkl
├── requirements.txt
└── README.md
```

## ✨ Features
- Customer churn prediction using ANN.
- Gender encoding and geography one-hot encoding.
- Feature scaling using a saved scaler.
- Reuse of a trained model for predictions.
- Interactive Streamlit application.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/kumkum06/ann-churn-prediction.git
```

### 2. Navigate to the project folder

```bash
cd ann-churn-prediction
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

## 📊 Dataset
The project uses the Churn Modelling dataset containing customer information and a churn indicator.

## 👩‍💻 Author
**Kumkum Saharawat**

GitHub: [kumkum06](https://github.com/kumkum06)