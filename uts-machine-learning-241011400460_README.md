# UTS Machine Learning - Linear Regression & Logistic Regression

**Nama:** SERILISELGIU HALAWA  
**NIM:** 241011400460  
**Kelas:** 05tplm003  
**Mata Kuliah:** Machine Learning  
**Kampus:** Universitas Pamulang  

---

## 📌 Ringkasan Hasil Eksperimen

### 📈 Bagian A - Linear Regression (`Ads_Data.csv`)
- **Random State:** 60
- **Model:** Normal Equation & Gradient Descent
- **Persamaan Regresi:** $\hat{y} = 4.8812 + 2.5290 \cdot X$
- **Metrik Evaluasi (Data Testing):**
  - **MAE:** 1.1052
  - **MSE:** 1.7891
  - **RMSE:** 1.3376
  - **$R^2$ Score:** 0.9521 (95.21%)

---

### 📧 Bagian B - Logistic Regression (`Email_Data.csv`)
- **Random State:** 60
- **Model:** Logistic Regression dengan Gradient Descent ($lpha = 0.1$, 10.000 iterasi)
- **Persamaan Logit:** $P(\text{Spam}) = \sigma(-4.1205 + 0.5124 \cdot \text{JumlahLink} + 0.4012 \cdot \text{KataPromo})$
- **Metrik Evaluasi (Threshold = 0.5):**
  - **Accuracy:** 93.33%
  - **Precision:** 100.00%
  - **Recall:** 90.91%
  - **F1-Score:** 95.24%
