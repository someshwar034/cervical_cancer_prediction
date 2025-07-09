# Cervical Cancer Detection

This project is focused on detecting the likelihood of cervical cancer using machine learning classification algorithms. The workflow includes data preprocessing, exploratory data analysis, model training, and evaluation.

## 📁 Dataset
The dataset used is `cervical_cancer.csv`, which contains medical information relevant to cervical cancer diagnosis. It includes various risk factors and screening test results.

## 📊 Exploratory Data Analysis
- Checked for missing values
- Visualized feature distributions using Seaborn
- Applied imputation for missing data
- Used `StandardScaler` for normalization

## 🔍 Model Training
Four machine learning models were trained:
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost**
- **AdaBoost**

The dataset was split using `train_test_split`, and models were evaluated using:
- Accuracy score
- Confusion matrix
- Classification report

## 🧪 Evaluation Metrics
Used the following metrics to assess model performance:
- Precision, Recall, F1-score
- Confusion Matrix
- Accuracy
  
## 📊 Results

### ✅ Training Data
*Confusion Matrix:* `[[621, 21], [6, 38]]`  
**Accuracy:** 96.1%  
**Precision:** 64.4%  
**Recall:** 86.4%  
**F1-Score:** 73.8%

---

### 🧪 Test Data
*Confusion Matrix:* `[[156, 5], [1, 10]]`  
**Accuracy:** 96.5%  
**Precision:** 66.7%  
**Recall:** 90.9%  
**F1-Score:** 76.9%

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `sklearn`

## 📌 How to Run
1. Clone the repository or download the notebook.
2. Ensure required libraries are installed using:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter notebook:
    ```bash
    jupyter notebook cervical_cancer_detection.ipynb
    ```
