# Predictive Analytics and Machine Learning in E-Commerce Operations

This project applies machine learning techniques to predict online shoppers’ purchasing intention using the **Online Shoppers Purchasing Intention** dataset.

The goal is to identify high-intent customers and support better decision-making in digital marketing and e-commerce operations.

---

## Project Objectives

- Predict whether a website session will result in a purchase
- Compare the performance of three machine learning models:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Evaluate models using ROC-AUC, Confusion Matrix, Precision, and Recall
- Provide actionable insights for marketing resource allocation and operational monitoring

---

## Dataset

- **Source**: Online Shoppers Purchasing Intention Dataset
- **Size**: 12,330 sessions
- **Target Variable**: `Revenue` (Purchase / No Purchase)
- **Key Features**: 
  - Administrative, Informational, and ProductRelated page metrics
  - Bounce Rates, Exit Rates, Page Values
  - Special Day, Month, Visitor Type, Weekend, etc.

---

## Models Used

| Model                  | Type                  | Purpose                              |
|------------------------|-----------------------|--------------------------------------|
| Logistic Regression    | Linear baseline       | Interpretable probabilistic model    |
| Random Forest          | Ensemble (Bagging)    | Strong non-linear performance        |
| Gradient Boosting      | Ensemble (Boosting)   | Highest predictive accuracy          |

---

## Key Results

- **Gradient Boosting** achieved the highest AUC (**≈ 0.927**)
- **Random Forest** followed closely (**≈ 0.915**)
- **Logistic Regression** baseline achieved (**≈ 0.891**)

Ensemble methods significantly outperformed the linear model, indicating that customer purchasing behaviour is driven by complex non-linear interactions.

---

## Project Structure
├── data/                          # Dataset
├── output/                        # Saved plots and results
├── PREDICTIVE ANALYTICS...Rmd     # Main analysis (R Markdown)
├── custom_roc_comparison_r.png    # ROC curve plot
├── custom_confusion_matrix_r.png  # Confusion matrix
└── README.md
## Technologies Used

- **R** & **RMarkdown**
- **caret** – model training and evaluation
- **randomForest** & **gbm** – ensemble models
- **pROC** – ROC and AUC analysis
- **ggplot2** & **tidyverse** – data visualisation
- **Git & GitHub** – version control

---

## How to Reproduce

1. Clone this repository
2. Open the `.Rmd` file in RStudio
3. Make sure the dataset is in the `data/` folder
4. Click **Knit** to generate the full HTML report

---

## Author

**Kivumbi Muganga**  
MSc Data Science (ongoing) – University of East London (UEL)  
Focus areas: Predictive Analytics, Machine Learning, Spatial Data Analysis
