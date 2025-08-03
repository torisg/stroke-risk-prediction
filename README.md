## 📌 Project Overview

This repository contains a stroke risk prediction project built in R using decision tree models. It includes: - A cleaned R Markdown file with full code and explanations and a polished case study summarizing the project for non-technical audiences.

The goal is to demonstrate how interpretable machine learning models like decision trees can help healthcare professionals identify at-risk patients early.

------------------------------------------------------------------------

## 📊 Features

-   Decision Tree Modeling: Compares a full model with all predictors to a simplified model using only the top variables
-   Variable Importance Analysis: Identifies key health and demographic factors linked to stroke
-   ROC & AUC Evaluation: Shows model performance visually and numerically
-   Imbalance Handling: Uses upsampling to better detect stroke cases
-   Interpretability: Extracts and explains model rules for clinical application

------------------------------------------------------------------------

## 📂 Repository Contents

-   stroke_model_comparison.Rmd – Full R Markdown with data prep, modeling, evaluation
-   Stroke_Risk_Prediction_Case_Study.docx – Word case study summary
-   stroke dataset.xlsx – Sample dataset 

------------------------------------------------------------------------

## ⚙️ How to Run

1.  Download the files.

2.  Open the stroke_model_comparison.Rmd in RStudio.

3.  Ensure required packages are installed:

    ``` r
    install.packages(c("readxl", "dplyr", "caret", "rpart", "rpart.plot", "pROC", "corrplot"))
    ```

4.  Load the dataset (update path in the R Markdown if needed).

5.  Knit to HTML or Word to view full analysis.

------------------------------------------------------------------------

## 📈 Key Findings

-   Age, glucose level, and hypertension are the strongest predictors of stroke.
-   The simplified decision tree (top 6 predictors) slightly improved AUC (0.83) and made interpretation easier for clinicians.
-   Upsampling improved the model’s ability to detect stroke cases in an imbalanced dataset.

------------------------------------------------------------------------

## 🚀 Next Steps

-   Add Random Forest or Gradient Boosting models for comparison.
-   Integrate SMOTE or cost-sensitive methods for even better sensitivity.
-   Package best model into a Shiny app for hospitals and clinics.

------------------------------------------------------------------------

## 🛠 Tools Used

-   R – Core language for analysis
-   caret – Modeling & cross-validation
-   rpart & rpart.plot – Decision tree modeling & visualization
-   pROC – ROC curve and AUC calculation
-   corrplot – Correlation heatmap

------------------------------------------------------------------------

## 📜 Data Source

The dataset used in this project comes from Kaggle:\
[Stroke Prediction Dataset by fedesoriano](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

**License:** The dataset is publicly available on Kaggle for educational and research use.
**Credit:** Created by Kaggle user *fedesoriano*.

------------------------------------------------------------------------

## 🤝 Contributions

This project was completed by **Tori Green** as part of a portfolio in data science and healthcare analytics. Contributions and feedback are welcome.


