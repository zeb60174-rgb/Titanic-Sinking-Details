# Titanic Survival Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/ML-Classification-brightgreen.svg)
![Accuracy](https://img.shields.io/badge/Accuracy-82.68%25-success.svg)

## Overview

A machine learning classification model that predicts passenger survival on the RMS Titanic. The project demonstrates complete data science workflow from exploratory analysis to model deployment, achieving **82.68% accuracy** with Random Forest algorithm.

## Dataset

- **Source**: Titanic Passenger Dataset
- **Target**: Survival status (0 = Did not survive, 1 = Survived)
- **Features**: Passenger demographics, ticket information, and cabin details

## Key Findings

| Rank | Feature | Importance |
|------|---------|-----------|
| 1 | Sex (Gender) | Most influential predictor |
| 2 | Fare Per Person | Wealth indicator |
| 3 | Age | Demographic factor |

**Insight**: Females had significantly higher survival rates. Ticket class and fare strongly correlated with survival chances.

## Models Developed

| Model | Accuracy |
|-------|----------|
| **Random Forest** ⭐ | **82.68%** |
| Neural Network | 81.50% |
| Logistic Regression | 80.90% |
| Support Vector Machine | 80.45% |
| K-Nearest Neighbors | 79.80% |

## Technologies

- **Python 3.8+**
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation
- **Scikit-learn** - Machine learning algorithms
- **Matplotlib & Seaborn** - Data visualization
- **TensorFlow/Keras** - Deep learning

## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
cd Titanic-Survival-Prediction

# Install dependencies
pip install -r requirements.txt
```

## View Analysis

Open the HTML file in your browser to see the complete analysis:
```bash
Titanic-Details-ShahZeb_html.html
```

## Project Workflow

1. **Exploratory Data Analysis** - Dataset overview and visualization
2. **Data Preprocessing** - Missing values, feature engineering, scaling
3. **Model Development** - Training 5 different classification algorithms
4. **Hyperparameter Tuning** - GridSearchCV optimization
5. **Model Evaluation** - Accuracy, precision, recall, and feature importance analysis

## Results
