
---

## 📊 Dataset
- **Source**: Provided dataset (`Fraud.csv`) containing transaction details.  
- **Features**: Includes numeric & categorical transaction details.  
- **Target**: Binary label (Fraudulent = 1, Legitimate = 0).  

⚠️ Note: The dataset is included for demonstration purposes only.

---

## 🛠️ Methodology
1. **Data Cleaning**  
   - Handle missing values.  
   - Outlier detection (IQR).  

2. **Data Preprocessing**  
   - Feature scaling (StandardScaler).  
   - Train/Test split.  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest Classifier  

4. **Evaluation Metrics**  
   - Confusion Matrix  
   - Precision, Recall, F1-score  
   - ROC Curve & AUC Score  

---

## 📈 Results
- Logistic Regression: Good baseline performance.  
- Random Forest Classifier: Better performance with higher ROC-AUC score.  

(📌 Add your actual numbers here — e.g., *Random Forest achieved ROC-AUC of 0.97*.)

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/reemak06/fraud_detection_ML.git
   cd fraud_detection_ML
