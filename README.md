# 🔥 Algerian Forest Fire Prediction – Flask ML App

This repository contains an **end-to-end Machine Learning project** deployed using **Flask**, which predicts forest fire risk based on environmental features from the **Algerian Forest Fires dataset**.

The project covers **EDA, model training, serialization, and web deployment**, making it a complete portfolio-ready ML application.

---

## 📂 Project Structure

```bash
FLASK_LAB/
│
├── models/
│   ├── ridge.pkl            # Trained Ridge Regression model
│   └── scaler.pkl           # StandardScaler used during training
│
├── notebook/
│   ├── algerian_forest_fire_datasets_EDA.ipynb   # Exploratory Data Analysis
│   ├── Model_Training.ipynb                      # Model training & evaluation
│   └── Algerian_forest_fires_dataset_UPDATE.csv  # Cleaned dataset
│
├── templates/
│   ├── home.html             # Home page UI
│   └── index.html            # Prediction result page
│
├── venv/                     # Virtual environment (ignored in production)
├── application.py            # Flask application entry point
└── README.md                 # Project documentation
