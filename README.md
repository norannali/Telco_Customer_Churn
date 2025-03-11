# **📊 Telco Customer Churn Prediction**

**📌 Overview**

This project focuses on predicting customer churn using Deep Learning models. We preprocess the Telco Churn dataset, apply SMOTE for handling class imbalance, and train Artificial Neural Network (ANN), Convolutional Neural Network (CNN), and Long Short-Term Memory (LSTM) models to compare their performance.

**📂 Dataset**

Source: telco_churn.csv

Target Variable: Churn

Features: Various customer attributes, including categorical and numerical data.

**🚀 Technologies Used**

Python (pandas, numpy, seaborn, matplotlib, imbalanced-learn)

Machine Learning (SMOTE, StandardScaler, LabelEncoder)

Deep Learning (TensorFlow/Keras: ANN, CNN, LSTM)

Model Evaluation (Accuracy, ROC-AUC, Classification Report)

**🔍 Data Preprocessing**

Handling Missing Values: Dropped rows with NaN values.

Encoding Categorical Features: Used LabelEncoder.

Feature Scaling: Applied StandardScaler to normalize numerical features.

Handling Class Imbalance: Used SMOTE to oversample minority class.

**📊 Model Implementation**

1️⃣ Artificial Neural Network (ANN)

3 hidden layers with ReLU activation

Dropout for regularization

Optimizer: Adam

2️⃣ ong Short-Term Memory (LSTM)

LSTM layer for sequential learning

Fully connected dense layers



**💡 Future Improvements**

Hyperparameter tuning for better accuracy.

Implementing advanced architectures (e.g., Transformers).

Deploying the model as a web service.

**🤝 Contributing**

Feel free to fork this repository, raise issues, or submit pull requests to improve the project.

**📜 License**

This project is licensed under the MIT License.

🚀 Let's predict customer churn effectively!

