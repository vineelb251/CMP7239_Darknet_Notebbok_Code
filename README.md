# 🚀 Darknet Traffic Classification using ML & DL  

## 📌 Project Overview  
This project focuses on **classifying network traffic** into different categories using both **Machine Learning (ML)** and **Deep Learning (DL)** techniques.  

The goal is to accurately distinguish between:  
- Non-Tor  
- NonVPN  
- Tor  
- VPN  

The models are trained on the **CICDarknet2020 dataset**, which contains network traffic features extracted using CICFlowMeter.

---

## 🎯 Objectives  
- Apply multiple ML and DL algorithms to a real-world cybersecurity dataset  
- Compare model performance using standard evaluation metrics  
- Identify the best-performing model for darknet traffic classification  
- Demonstrate practical application of AI in cybersecurity  

---

## 📂 Dataset Information  
- **Dataset Name:** CICDarknet2020  
- **File Used:** `Darknet.csv`  
- **Type:** Multi-class classification  
- **Features:** Network traffic flow features  
- **Target Variable:** Traffic Category (Non-Tor, NonVPN, Tor, VPN)  

---

## 🧠 Models Implemented  

### 🔹 Machine Learning Models  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  

### 🔹 Deep Learning Models  
- Artificial Neural Network (ANN)  
- Multilayer Perceptron (MLP)  

---

## ⚙️ Workflow  

### 1. Data Preprocessing  
- Handling missing values  
- Removing infinite values  
- Encoding categorical labels  
- Feature scaling (Normalization/Standardization)  

### 2. Exploratory Data Analysis (EDA)  
- Data distribution analysis  
- Feature inspection  
- Class balance verification  

### 3. Model Training  
- Training ML and DL models  
- Hyperparameter tuning (where applicable)  

### 4. Model Evaluation  
Models are evaluated using:  
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

---

## 📊 Results Summary  

The models were compared based on performance metrics, and:  

✅ **Random Forest achieved the best overall performance**  
- High accuracy  
- Strong generalization  
- Robust against overfitting  

---

## 🛠️ Technologies Used  
- Python  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  
- TensorFlow / Keras  

---

## 📥 Clone the Repository  

```bash
git clone https://github.com/your-username/darknet-traffic-classification.git
cd darknet-traffic-classification
```

---

## 📈 Key Highlights  
- Combines **ML + DL approaches** in one project  
- Works on a **real cybersecurity dataset**  
- Demonstrates **end-to-end pipeline**  
- Suitable for **academic + portfolio use**  

---

## 🔐 Applications  
- Network Intrusion Detection Systems (IDS)  
- Cybersecurity Monitoring  
- Darknet Traffic Analysis  
- Threat Intelligence Systems  

---

## 👤 Author  

**Name:** Vineel Bokkinala  
**Student ID:** 25165675  

---

## 📌 Future Improvements  
- Implement advanced deep learning models (CNN, LSTM)  
- Use real-time streaming data  
- Apply feature selection techniques  
- Deploy as a web-based detection system  

---

## ⭐ If you like this project  
Give it a star ⭐ on GitHub and feel free to fork it!  
