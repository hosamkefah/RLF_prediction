# 📡 RLF Prediction

This repository contains a Jupyter Notebook for **Radio Link Failure (RLF) prediction** using machine learning techniques.  
Radio Link Failure is a key challenge in mobile communication networks, often leading to dropped calls, poor connectivity, and degraded user experience.  
By predicting RLF in advance, operators can take preventive measures to enhance network reliability.

---

## 🔍 Project Overview
The notebook demonstrates the full pipeline of an ML project:
1. **Data Handling** – loading raw network data, cleaning, and preparing features.  
2. **Exploratory Data Analysis (EDA)** – statistical summaries, correlations, and visualization of network parameters.  
3. **Feature Engineering** – normalization, encoding, and selection of predictive features.  
4. **Model Training** – applying multiple machine learning algorithms for RLF prediction.  
5. **Evaluation** – comparing models using classification metrics and visualization tools.  
6. **Insights** – understanding which features contribute most to RLF events.  

---

## ⚙️ Requirements
- Python 3.8+  
- Jupyter Notebook  

Core libraries used:
- `pandas` – data manipulation  
- `numpy` – numerical computations  
- `scikit-learn` – ML models and evaluation  
- `matplotlib`, `seaborn` – visualization  

---

## 📂 Dataset
The notebook expects a dataset with **radio and network-level measurements**.  
Typical features may include:
- **Signal Strength (RSRP, RSSI)**  
- **Signal Quality (SINR, RSRQ)**  
- **Mobility Events (handover attempts, failures)**  
- **Network Load Indicators**  
- **Time/Location-based parameters**  

⚠️ *The dataset is not included in this repository. Please update paths and preprocessing steps according to your dataset.*  

---

## 🤖 Models Implemented
The notebook trains and compares several machine learning algorithms, such as:
- Logistic Regression  
- Decision Trees  
- Random Forest  
- Support Vector Machine (SVM)  
- Gradient Boosting  

Each model is evaluated and benchmarked to identify the best-performing approach for RLF prediction.

---

## 📊 Evaluation Metrics
Performance is measured using:
- **Accuracy** – overall correctness of predictions  
- **Precision & Recall** – balance between false alarms and missed failures  
- **F1-Score** – harmonic mean of precision and recall  
- **Confusion Matrix** – classification breakdown  
- **ROC Curve & AUC** – probability-based evaluation  

---
