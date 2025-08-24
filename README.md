# 🔐 Credit Card Fraud Detection

## 🔹 Introduction
Credit card fraud is one of the most significant issues in the financial industry, leading to huge monetary losses every year.  
This project focuses on detecting fraudulent transactions using **Machine Learning models** to help financial institutions identify suspicious activities in real time.

---

## 🔹 Problem Statement
The dataset is highly imbalanced since fraudulent transactions make up a very small portion of the total.  
The objective is to:
1. Analyze transaction patterns.  
2. Handle class imbalance effectively.  
3. Train machine learning models that can accurately classify fraudulent vs. non-fraudulent transactions.  
4. Evaluate models based on metrics suitable for imbalanced data.  

---

## 🔹 Methodology

### 1. Data Preprocessing
- Loaded and explored the dataset.  
- Checked for missing/null values (none found).  
- Normalized/standardized transaction features.  
- Addressed **class imbalance** using **SMOTE (Synthetic Minority Oversampling Technique)**.  

### 2. Exploratory Data Analysis (EDA)
- Distribution of legitimate vs. fraudulent transactions.  
- Correlation heatmap of features.  
- Amount vs. time distribution to detect fraud patterns.  

### 3. Models Implemented
Several classification algorithms were trained and compared:
- **Logistic Regression**  
- **Random Forest Classifier**  
- **XGBoost**  
- **LightGBM**  
- **Gradient Boosting**  

### 4. Evaluation Metrics
Since the dataset is imbalanced, standard accuracy is not sufficient.  
We used:
- **Confusion Matrix**  
- **Precision, Recall, F1-Score**  
- **ROC-AUC Score**  
- **PR-AUC Curve**  

---

## 🔹 Results & Insights

### 📊 Model Comparison
- **Logistic Regression** – Simple, interpretable, but lower recall.  
- **Random Forest** – Balanced performance with good recall.  
- **XGBoost** – High precision, slightly better ROC-AUC.  
- **LightGBM** – Fast training, strong performance on imbalanced data.  
- **Gradient Boosting** – Competitive but slower training.  

### 📊 Key Insights
- Fraudulent transactions are usually of **smaller amounts** compared to legitimate ones.  
- **Recall** is more critical than accuracy, since false negatives (missed frauds) are more costly than false positives.  
- **XGBoost & LightGBM** provided the best trade-off between precision and recall.  

---

## 🔹 Conclusion
- Machine learning models can effectively detect fraudulent activities in real-world financial datasets.  
- Handling **class imbalance** is crucial for achieving high recall.  
- Ensemble models like **XGBoost** and **LightGBM** showed the best overall performance.  
- This system can be integrated into financial pipelines to minimize fraudulent losses.  

---

## 🔹 Future Enhancements
- Use **Deep Learning (ANN, Autoencoders)** for anomaly detection.  
- Integrate **real-time fraud detection** using streaming data.  
- Apply **Graph Neural Networks (GNNs)** to model transaction relationships.  
- Deploy the model as an **API / Dashboard** for financial institutions.  

---

## 👩‍💻 Author
**Meenal Gaikwad**
