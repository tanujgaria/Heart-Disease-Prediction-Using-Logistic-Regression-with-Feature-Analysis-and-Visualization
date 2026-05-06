
# Heart-Disease-Prediction-Using-Logistic-Regression-with-Feature-Analysis-and-Visualization
# ❤️ Heart Disease Prediction using Logistic Regression

## 📌 Overview

This project presents a **machine learning-based approach** for predicting heart disease using **Logistic Regression**. The model is trained on a clinical dataset containing patient health parameters and is capable of predicting whether a person is likely to have heart disease or not.

The project focuses on:

* Data preprocessing
* Feature analysis
* Model training
* Performance evaluation
* Visualization of insights

---

## 📊 Dataset

The dataset consists of **303 patient records** with **13 clinical features**, including:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG (restecg)
* Maximum Heart Rate (thalach)
* Exercise Induced Angina (exang)
* Oldpeak
* Slope
* Number of Vessels (ca)
* Thalassemia (thal)

**Target Variable:**

* `1` → Heart Disease
* `0` → No Heart Disease

---

## ⚙️ Methodology

The project follows a structured machine learning pipeline:

1. Data Collection
2. Data Preprocessing

   * Handling missing values
   * Feature separation (X, Y)
3. Train-Test Split (80:20)
4. Model Training using Logistic Regression
5. Model Evaluation using Accuracy
6. Prediction on new input data

---

## 📈 Results

* **Training Accuracy:** 85.12%
* **Testing Accuracy:** 81.97%

The model demonstrates **good generalization** with minimal overfitting.

---

## 🔍 Visualization

The project includes:

* Correlation Heatmap
* Feature-wise Analysis (Sex, Chest Pain, etc.)
* Data Distribution Graphs

These visualizations help in understanding the relationship between features and heart disease.

---

## 🧠 Key Insights

* Chest pain type and maximum heart rate are strong predictors
* Exercise-induced angina and oldpeak negatively influence prediction
* Fasting blood sugar has minimal impact
* Heart disease is more common in individuals aged 45–65

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name
```

### 2. Navigate to project folder

```bash
cd your-repo-name
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook/script

* Open `.ipynb` in Jupyter Notebook
  OR

```bash
python main.py
```

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Structure

```bash
├── data/                # Dataset
├── notebooks/           # Jupyter notebooks
├── src/                 # Source code
├── images/              # Graphs & visualizations
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```

---

## 📌 Future Improvements

* Add advanced ML models (Random Forest, SVM)
* Hyperparameter tuning
* Add ROC curve and confusion matrix
* Deploy as a web application

---

## 🔗 Research Paper

This project is part of a research study on heart disease prediction.
*(Add your paper link here if available)*

---

## 👨‍💻 Author

**Tanuj Garia**

---

## ⭐ Support

If you find this project useful, please consider giving it a ⭐ on GitHub!
