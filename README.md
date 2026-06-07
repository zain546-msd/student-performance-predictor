# student-performance-predictor
ML project — Student grade prediction using Logistic Regression
# Student Performance Predictor 🎓

A machine learning project that predicts student final grades (A/B/C/D/F)
using Logistic Regression on the UCI Student Performance Dataset.

## Dataset
- **Source:** UCI Machine Learning Repository (Cortez & Silva, 2008)
- **File:** student-por.csv (Portuguese Language Course)
- **Size:** 649 students, 33 features

## Features Used
| Feature | Description |
|---------|-------------|
| studytime | Weekly study time (1–4 scale) |
| failures | Number of past class failures |
| absences | Number of school absences |
| Medu | Mother's education level |
| Fedu | Father's education level |
| goout | Going out with friends (1–5) |
| Walc | Weekend alcohol consumption |
| health | Current health status |
| internet | Internet access at home |
| romantic | In a romantic relationship |

## Model Performance
| Metric | Score |
|--------|-------|
| Training Accuracy | ~84% |
| Test Accuracy | ~82% |
| Macro F1-Score | ~0.79 |
| Cross-Val (k=5) | ~81% |

## Algorithm
- Logistic Regression (Multinomial)
- StandardScaler normalization
- Stratified 80/20 train-test split
- 5-Fold Cross Validation

## How to Run
1. Open the notebook on Kaggle: [Link here]
2. Add dataset: `larsen0966/student-performance-data-set`
3. Run all cells

## Tools & Libraries
- Python 3.12
- scikit-learn
- pandas, numpy
- matplotlib, seaborn

## Author
**Zain Ullah**  
ML Project — June 2026
