# 📌 Overview
This project develops a machine learning pipeline to predict stroke risk based on patient health data. It explores various classification algorithms, evaluates their performance, and identifies key risk factors contributing to stroke prediction.

# 🧠 Models Implemented
- Random Forest Classifier
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost
- Decision Tree Classifier

# 📊 Key Metrics Evaluated
- Accuracy
- Precision & Recall
- F1-Score
- AUC-ROC Score
- Confusion Matrix Analysis

# 🛠️ Tech Stack
- Python 3
- Pandas & NumPy (Data Processing)
- scikit-learn (ML Models)
- Matplotlib & Seaborn (Visualizations)
- XGBoost (Gradient Boosting)

# 📈 Results
The study evaluated six machine learning models for stroke prediction using a dataset of 40,910 patient records. The models were assessed based on accuracy, precision, recall, F1-score, and AUC-ROC. The key findings are summarized below:

<img width="801" alt="image" src="https://github.com/user-attachments/assets/92f09862-b5a4-4340-afb0-8f7ebbc73e9f" />

The Random Forest Classifier (RFC) emerged as the most reliable model for stroke prediction, offering near-perfect accuracy (99.81%) while maintaining high precision and recall. These findings suggest that ensemble learning methods (RFC, XGBoost) are superior for medical risk prediction compared to traditional models like Logistic Regression. Future work could explore deep learning and image-based data (e.g., CT scans) to further enhance predictive performance.
