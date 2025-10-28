# **Title:** Company-Bankruptcy-Prediction-using-Decision-Trees-ML_Mini_Project 
**Course:** UE23CS352A  
**Academic Year:** 2025  
**Semester:** 5th Sem  
**Campus:** EC  
**Branch:** AIML  
**Section:** B  
**Team number:** B3
**Team Members:**
- [@sriyaa-p](https://github.com/sriyaa-p) - Sriya Panda (PES2UG23AM104)
- [@Srinidhi8105](https://github.com/Srinidhi8105) - Srinidhi S (PES2UG23AM103)


# **Company Bankrupcy Prediction (Using Decision Tree)**

## **Problem Statement :**
The goal of this project is to **predict whether a company is likely to go bankrupt, using a Decision Tree** classification model

Bankruptcy prediction is crucial for:

1.   Investors and creditors assessing financial risk
2.   Early warning systems for companies
3. Supporting data-driven financial decisions

## **Dataset Information**

**Source:** UCI Machine Learning Repository – Taiwanese Bankruptcy Prediction Dataset

**Years Covered:** 1999–2009

**Instances:** 6,819 companies

**Features:** 95 financial ratios (X1–X95)

**Target:** Y = 1 → bankrupt, Y = 0 → not bankrupt

The dataset includes key financial ratios such as ROA, operating profit, debt ratios, cash flow, equity ratios, current ratio, and more.

## **Objective**

Develop a Decision Tree model using scikit-learn to classify companies as bankrupt or not, including:

1. Data preprocessing
2. Feature Reduction using PCA
3. Decision Tree training
4. Evaluation with 5 - cross-validation
5. Comparision Before Tuning and After Tuning

## **Setup and Instructions**
(If we run on system)
- **1. Clone Repo**
git clone https://github.com/<your-username>/Company-Bankruptcy-Prediction.git
cd Company-Bankruptcy-Prediction

- **2. Install dependencies**
pip install -r requirements.txt

- **3. Launch NB**

**(For Colab)**
1. Go to Google Colab
2. Click File → Upload Notebook.
3. Upload your file: Company_Bankruptcy_Pred.ipynb
4. Upload data.csv while running Loading Data code cell.

 **Execute all cells sequentially (Runtime → Run All) to:**
1. Load and preprocess the dataset
2. Apply PCA for dimensionality reduction
3. Train and evaluate the Decision Tree model
4. Visualize metrics and results
