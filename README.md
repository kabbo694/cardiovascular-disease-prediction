# 🫀 Cardiovascular Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.9+-blue?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange?style=flat&logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

> A complete end-to-end Machine Learning project to predict cardiovascular disease using clinical and lifestyle features.

---

## 🎯 Problem Statement
Cardiovascular disease is the #1 cause of death globally (~17.9M deaths/year). This project builds and compares two ML models to predict whether a patient has CVD based on clinical data.

---

## 📊 Dataset
| Property | Details |
|----------|---------|
| Source | [Kaggle — Cardiovascular Disease](https://www.kaggle.com/datasets/colewelkins/cardiovascular-disease) |
| Rows | 70,000 patient records |
| Target | `cardio` (0 = No Disease, 1 = Disease) |

---

## 🤖 Models Used
| Model | Configuration |
|-------|--------------|
| Logistic Regression | `solver=lbfgs`, `max_iter=1000` |
| Decision Tree | `max_depth=6`, `min_samples_split=50` |

---

## 📈 Results
| Metric | Logistic Regression | Decision Tree |
|--------|:-------------------:|:-------------:|
| Accuracy | ~0.733 | ~0.718 |
| Precision | ~0.738 | ~0.720 |
| Recall | ~0.726 | ~0.710 |
| F1 Score | ~0.732 | ~0.715 |
| ROC-AUC | ~0.800 | ~0.768 |

✅ **Logistic Regression wins** — higher ROC-AUC and better recall.

---

## ▶️ How to Run

### Google Colab
1. Upload the `.ipynb` file to [Colab](https://colab.research.google.com/)
2. Upload `cardio_train.csv`
3. Run all cells

### Local
```bash
git clone https://github.com/YourUsername/cardiovascular-disease-prediction.git
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook cardiovascular_disease_prediction.ipynb
```

---

## 🧠 Conclusion
- Age, blood pressure, and cholesterol are the strongest CVD predictors
- Logistic Regression outperforms Decision Tree on this dataset
- Future work: XGBoost, Random Forest, k-fold cross-validation

---

## 👤 Author
**Shifat Rahman Kabbo**
- LinkedIn: [www.linkedin.com/in/shifat-rahman-kabbo-964322311]


⭐ If you found this helpful, please star the repo!
