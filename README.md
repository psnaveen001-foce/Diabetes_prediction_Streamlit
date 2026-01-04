# 🧬 Diabetes Prediction System
End-to-End Machine Learning & Streamlit Web Application

# 📌 Project Overview

This project is an end-to-end Machine Learning application that predicts whether a person is likely to have Diabetes based on medical and lifestyle attributes.
It covers the entire ML lifecycle — from data preprocessing and model training to model deployment using Streamlit.

The application allows users to input patient details via a web UI and receive real-time predictions using a trained Decision Tree model.

# 🚀 Key Features

* Data preprocessing & encoding

* Duplicate and missing value checks

* Supervised ML model training

* Model serialization using Pickle

* Interactive Streamlit Web UI

* Cloud-based deployment using Cloudflare Tunnel

# 🧠 Tools & Technologies Used
Programming & Environment

* Python 3

* Google Colab

* Data Handling & ML

* pandas

* numpy

* scikit-learn

* Label Encoding

* Train–Test Split

* Decision Tree Classifier

* Model Deployment

* pickle (model serialization)

* streamlit (web application)

* cloudflared (public URL tunneling)

# 📂 Dataset

* Dataset Name: diabetes_prediction_dataset.csv

* Target Variable: diabetes

# Features Used:

* Gender

* Age

* Hypertension

* Heart Disease

* Smoking History

* BMI

* HbA1c Level

* Blood Glucose Level

# 🔄 Project Workflow
1️⃣ Data Loading & Exploration

* Loaded CSV using pandas

Checked:

* Data types

* Duplicates

* Missing values

2️⃣ Data Preprocessing

* Encoded categorical features using LabelEncoder

* gender

* smoking_history

* Separated features (X) and target (y)

3️⃣ Model Training

* Split data into training and testing sets (90:10)

* Trained a Decision Tree Classifier

* Evaluated class distributions

4️⃣ Model Persistence

* Saved trained model as brain.pkl using Pickle

* Reloaded model for inference

5️⃣ Streamlit Web App

* User-friendly input form

* Real-time prediction output:

✅ Low Risk

⚠️ High Risk

6️⃣ Deployment

* Streamlit app launched from Colab

* Public access enabled via Cloudflare Tunnel

# 🧪 Model Used

* Algorithm: Decision Tree Classifier

Reason:

* Easy to interpret

* Works well with mixed numerical & categorical data

* Fast training and inference

# 🖥️ Streamlit App Inputs

| Feature             | Input Type |
| ------------------- | ---------- |
| Age                 | Number     |
| Gender              | Dropdown   |
| Hypertension        | Binary     |
| Heart Disease       | Binary     |
| Smoking History     | Dropdown   |
| BMI                 | Number     |
| HbA1c Level         | Number     |
| Blood Glucose Level | Number     |

# 📈 Prediction Output

* Low Risk: Patient is NOT Diabetic

* High Risk: Patient is likely Diabetic

* Clear visual feedback using Streamlit alerts.

# 👨‍💻 Author

Naveen Kumar
Aspiring Data Scientist | Machine Learning & Analytics
Experienced in:

Data Science

Machine Learning
