# 📊 Data Quality vs Model Performance

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

### A Machine Learning research project

Investigating how different data quality issues affect machine learning model performance, using Python, Scikit-learn, and the Titanic dataset.

---

## 🎯 Project Goal

The objective of this research is to investigate how different data quality problems influence machine learning performance, and whether data quality matters more than model choice.

The project evaluates several common real-world data issues:

- Missing data
- Noisy labels
- Feature selection
- Model comparison

Three machine learning algorithms are compared throughout the experiments:

- Logistic Regression
- Decision Tree
- Random Forest

---

## 🛠 Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

---

## 📂 Project Structure
```
data-quality-vs-model-performance/
├── datasets/                          # Original datasets
│
├── images/                            # Graphs and visualizations
│   ├── accuracy_decision_tree_missing.png
│   ├── accuracy_feature_selection.png
│   ├── accuracy_missing_data_regression.png
│   ├── accuracy_noisy_data_regression.png
│   ├── comparison_accuracy.png
│   ├── comparison_f1.png
│   ├── f1_decision_tree_missing.png
│   ├── f1_feature_selection.png
│   ├── f1_missing_data.png
│   ├── f1_noise_impact.png
│   ├── f1_random_forest_missing.png
│   ├── model_accuracy_comparison.png
│   ├── model_f1_comparison.png
│   └── random_forest_missing_accuracy.png
│
├── notebooks/                         # Google Colab notebooks
│   ├── 01_logistic_regression.ipynb
│   ├── 02_decision_tree.ipynb
│   ├── 03_random_forest.ipynb
│   ├── 04_missing_data.ipynb
│   ├── 05_noisy_data.ipynb
│   ├── 06_feature_selection.ipynb
│   ├── 07_data_quality_comparison.ipynb
│   ├── 08_decision_tree_missing_data.ipynb
│   ├── 09_random_forest_missing_data.ipynb
│   └── 10_model_comparison_missing_data.ipynb
│
├── results/                           # Experimental results (CSV)
│   ├── comparison_data_quality.csv
│   ├── decision_tree_missing_data.csv
│   ├── features_data_results.csv
│   ├── logistic_regression_missing_data.csv
│   ├── missing_data_results.csv
│   ├── noisy_data_results.csv
│   └── random_forest_missing_data.csv
│
├── report/                            # Final research paper
│
├── src/                                # Future reusable Python modules
│
├── requirements.txt
└── README.md
```
---

## ✅ Current Progress

- [x] Data preprocessing
- [x] Missing data experiment
- [x] Noisy data experiment
- [x] Feature selection experiment
- [x] Model comparison

- [ ] Hyperparameter tuning
- [ ] Cross-validation
- [ ] Final report

---

## 📈 Current Results

The project currently compares three machine learning models under different data quality conditions.

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Logistic Regression | 0.816 | – | – | – |
| Decision Tree | 0.821 | – | – | – |
| Random Forest | 0.827 | 0.877 | 0.676 | 0.763 |

Experiments completed:

- Missing Data
- Noisy Labels
- Feature Selection
- Model Comparison

Visualizations are available inside the [`images/`](./images) folder.

---

## 🚀 Future Improvements

- Hyperparameter optimization
- Cross-validation
- ROC curve analysis
- Precision-recall curves
- Feature importance
- XGBoost
- LightGBM

---

## 👨‍💻 Author

Ivan Medvedev
High school student interested in Machine Learning, Artificial Intelligence, and Data Science.

GitHub: [@mksmedvedmain-boop](https://github.com/mksmedvedmain-boop) · Repo: [data-quality-vs-model-performance](https://github.com/mksmedvedmain-boop/data-quality-vs-model-perfomance)e Learning, Artificial Intelligence, and Data Science.

GitHub: mksmedvedmain-boop
