# 🌸 Iris Flower Classification

This project develops a machine learning model to classify **Iris flower species** based on petal and sepal dimensions. The model identifies among **three species**:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## 🎯 Objectives
- Build a classifier for Iris species
- Identify most important features affecting classification
- Evaluate multiple ML models and compare their accuracy
- Visualize data relationships and model performance

---

## 📊 Dataset
The dataset used for this project contains 150 samples, each with four features: 
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each sample is labeled with one of the three Iris species, providing a balanced representation for training and evaluation.

---

## 🔧 Tools and Libraries
- Python
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

## 📈 EDA and Feature Analysis

- Histograms and scatter plots for visual distribution  
- Correlation matrix using `seaborn` heatmap  
- Feature importance using `SelectKBest` with `mutual_info_classif`

---

## 🧠 Models Used

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier

Each model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

Best accuracy achieved: **~100% with KNN**

---

## 🚀 How to Run

1. Clone this repository or download the ZIP  
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook to execute the analysis and visualize the results.

---

## 📊 Conclusion and Future Work

This project successfully classified Iris species with high accuracy. Future work could involve:
- Exploring additional models such as Support Vector Machines (SVM) and Random Forests
- Implementing hyperparameter tuning for improved performance
- Expanding the dataset to include more diverse samples for better generalization


