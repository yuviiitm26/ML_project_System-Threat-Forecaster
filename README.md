# 🛡️ System-Threat-Forecaster

## 📌 Project Overview
**System-Threat-Forecaster** is a machine learning project developed as part of a competition aimed at predicting the probability of a system being infected by various families of malware. The solution is based on system telemetry data collected from antivirus threat reports. The project demonstrates how machine learning can be used in real-world cybersecurity applications to enhance threat detection and response.

## 🎯 Objective
To build predictive models that estimate the likelihood of system infection by different malware families based on telemetry attributes.

## 📂 Dataset Description
The dataset comprises anonymized telemetry data and malware infection labels collected by antivirus software. Features include system configuration, usage behavior, installed applications, and security settings.

> Note: Due to licensing restrictions, the dataset is not publicly available.

## 🧰 Technologies & Tools
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, scikit-learn, XGBoost
- **Algorithms Used**:  
  - XGBoost ✅ (Best performing model)  
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  
  - AdaBoost

## ⚙️ Methodology
1. **Data Preprocessing**:  
   - Handled missing values and encoded categorical features.
   - Normalized/standardized numerical features.
2. **Feature Engineering**:  
   - Feature selection based on correlation and importance.
   - Dimensionality reduction for noise elimination.
3. **Model Training & Evaluation**:  
   - Applied multiple ML algorithms.
   - Evaluated models using accuracy, F1-score, and ROC-AUC.
   - Tuned hyperparameters using cross-validation.

## ✅ Results
- Among all models, **XGBoost** achieved the highest accuracy and robustness.
- Demonstrated strong generalization on unseen test data.
- Validated importance of ensemble learning for threat detection.

## 📈 Key Learnings
- Hands-on experience in handling real-world, high-dimensional telemetry data.
- Improved understanding of cybersecurity threats and how ML can mitigate them.
- Strengthened skills in model selection, evaluation, and optimization.

## 🚀 Future Work
- Integrate deep learning approaches like DNNs or LSTM for sequence-based detection.
- Deploy the model in a simulated antivirus environment for real-time detection.
- Explore feature importance to assist security teams with threat explainability.

## 📌 Author
**Yuvraj Gosain**  
BS in Data Science and Applications, IIT Madras  
GitHub: [github.com/YuvrajGosain](https://github.com/yuviiitm26)  
LinkedIn: [[linkedin.com/in/YuvrajGosain](https://linkedin.com/in/YuvrajGosain](https://www.linkedin.com/in/yuvraj-gosain-b542a3250?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app ))

---

> ⚠️ **Note**: This project is intended for educational and research purposes. No real malware samples were used in this work.

