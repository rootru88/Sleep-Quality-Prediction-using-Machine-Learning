# 🌙 Sleep Quality Prediction using Machine Learning

A machine learning project that predicts a person's **Sleep Quality Score (1–10)** using health and lifestyle information. This project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and a Streamlit web application for predictions.

> **Note:** This project was built as part of my machine learning learning journey.

---

## 📌 Project Overview

The goal of this project is to predict sleep quality from health-related features such as:

- Gender
- Physical Activity Level
- Daily Steps
- Blood Pressure
- BMI Category
- Sleep Disorder Status
- Occupation

The project follows a complete ML workflow:

1. Data cleaning
2. Exploratory Data Analysis (EDA)
3. Feature engineering
4. Model training
5. Model evaluation
6. Interactive web application

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Streamlit
- Joblib

---

## 📊 Exploratory Data Analysis

The project includes several visualizations such as:

- Distribution of Sleep Quality
- Correlation Heatmap
- BMI vs Sleep Quality
- Occupation vs Sleep Quality

These visualizations helped understand relationships between different health metrics and sleep quality.

---

## ⚙ Data Preprocessing

The dataset was prepared using several preprocessing steps:

- Removed unnecessary columns
- Split Blood Pressure into Systolic and Diastolic values
- Removed duplicate records
- Label encoded Gender
- One-hot encoded Occupation and Sleep Disorder
- Converted BMI Category into numerical values
- Train/Test split

---

## 🤖 Machine Learning Model

Model used:

- Random Forest Regressor

Evaluation metrics:

- Mean Absolute Error (MAE)
- R² Score
- 5-Fold Cross Validation
- Feature Importance Analysis

---

## 🌐 Streamlit Application

The project also includes a Streamlit web application where users can:

- Enter health metrics
- Predict sleep quality
- Receive personalized lifestyle suggestions

---

```

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/Sleep-Quality-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app.py
```

---

## 📈 Future Improvements

- Compare multiple ML algorithms
- Hyperparameter tuning
- Improve feature engineering
- Better handling of categorical variables
- Model deployment on the cloud
- More comprehensive user interface

---

## 📚 What I Learned

Through this project I practiced:

- Data preprocessing
- Exploratory Data Analysis
- Feature engineering
- Machine Learning workflows
- Model evaluation
- Cross-validation
- Building an interactive ML application with Streamlit

---

## 👨‍💻 Author

**Muhammad Hassan**

Bachelor's Student in Artificial Intelligence

Learning Machine Learning and Artificial Intelligence through hands-on projects.
