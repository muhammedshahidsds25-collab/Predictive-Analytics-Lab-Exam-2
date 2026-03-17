# Predictive-Analytics-Lab-Exam-2
Classification model with EDA, decision boundary, and performance evaluation


## 📌 Objective

The objective of this project is to perform a binary classification task using machine learning. The workflow includes Exploratory Data Analysis (EDA), model building, visualization of decision boundary, and performance evaluation.

---

## 📊 Dataset

The dataset used contains:

* **Feature1**
* **Feature2**
* **Target** (Yes/No)

### Preprocessing Steps:

* Removed missing values in the target column
* Removed outliers (Feature1 > 100)
* Converted target labels:

  * Yes → 1
  * No → 0

---

## 🔍 Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset:

* Scatter plot to visualize relationship between features
* Correlation heatmap to analyze relationships
* Checked dataset size and structure

---

## 🤖 Model Used

* **Logistic Regression**
* Implemented using a **Pipeline**:

  * StandardScaler (feature scaling)
  * Logistic Regression (with balanced class weights)

---

## ⚙️ Methodology

1. Data loading and cleaning
2. Feature selection (Feature1, Feature2)
3. Train-test split (80:20 with stratification)
4. Model training using pipeline
5. Decision boundary visualization
6. Model evaluation

---

## 📈 Decision Boundary

* Decision boundary plotted using meshgrid
* Shows how the model separates classes in feature space

---

## 📊 Model Evaluation

Performance was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Classification Report**

  * Precision
  * Recall
  * F1-score

---

## ✅ Results

The Logistic Regression model effectively classifies the dataset with clear separation between classes. Feature scaling and class balancing improved performance.

---

## 📁 Project Structure

* `main.ipynb` → Implementation code
* `dataset.csv` → Input dataset
* Decision boundary and confusion matrix plots generated during execution

---

## 🚀 Conclusion

The project demonstrates a complete machine learning workflow for classification, including EDA, model training, visualization, and evaluation. Logistic Regression proved to be an effective model for this dataset.

---
