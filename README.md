# Binomial GLM Models for Predicting Probability of Default in Imbalanced Data

This repository contains the materials and code related to my bachelor thesis. 

The thesis explores the application of binomial generalized linear models (GLM) for predicting the probability of default (PD) in credit scoring contexts, with a particular focus on imbalanced data. Performance comparisons are conducted between logistic regression (symmetric link function) and complementary log-log regression (asymmetric link function).

---

## ⚠️ Disclaimer
The documents and all code comments are written in **Italian** because I submitted the thesis in Italian. If you have any questions or need clarification in English, feel free to reach out to me.

---

## 📘 Thesis Overview
- **Author**: Mariapia Tedesco  
- **Supervisors**: Prof.ssa Marcella Niglio, Prof.ssa Marialuisa Restaino  
- **Academic Year**: 2022/2023  
- **Degree Program**: Statistics for Big Data, University of Salerno  

### Abstract
A large part of the work carried out by financial intermediaries lies in taking on risks, with the primary one being credit risk, which is defined as the risk of insolvency of a borrower requesting a loan. Given the centrality of lending activity, not only within individual banks but also within the entire banking ecosystem, the Basel Committee on Banking Supervision has established that banks are required to measure the one-year probability of insolvency for each client in order to calculate the risk-weighted exposure of loans. To this end, they can rely on internal rating systems by calculating their own estimates for the probability of default (PD).

This is the starting point for this work, which aims to investigate the use of binomial GLM models for predicting the probability of insolvency. Logistic regression, based on a symmetric link function, is one of the most widely used models in academic literature for calculating the probability of default. However, it shows significant disadvantages in studies involving highly imbalanced data, a characteristic typical of data in this context. Therefore, its performance is compared with that of the complementary log-log regression, which uses an asymmetric link function derived from the cumulative distribution function of the random variable called Generalized Extreme Value (GEV).

---

## 🏗️ Repository Structure
- `Index_Intro`: Contains the Table of Contents and the Introduction of my thesis.
- `Chapter3`: The chapter related to the application of the models on real-world data.
- `BERKA/`: Includes datasets used for model training and evaluation. 
- `scripts/`: Scripts (R Markdown) for data preprocessing, model building, validation, and comparison. Refer to `scripts/README_scripts` for more details.

---

## 🚀 A (Very) Brief Overview of My Thesis

### Chapter 1: Credit Risk and Credit Scoring
- The importance of credit risk management in the banking ecosystem.
- The Basel Accords and the use of internal rating systems for predicting PD.
- The *credit scoring* methods.

### Chapter 2: Statistical Models
- In-depth explanation of GLM models and binary GLM models.
- The rationale for using specific link functions.
- Generalized Extreme Value distribution.
- Logit model and Complementary log-log model.
- Parameter estimation.
- Model validation and selection.
- From regression to classification.

### Chapter 3: Statistical Analysis
- Data pre-processing and Exploratory Data Analysis.
- Model construction, validation, and selection.
- Comparison of the models in terms of goodness-of-fit and predictive accuracy.

---

## 📊 Main Findings
- Logistic regression underestimates probabilities for rare events due to its symmetric link function.
- Complementary log-log regression shows improved performance for imbalanced datasets, leveraging its focus on extreme values.

---

## 🛠️ Technologies Used
- **R**: For statistical modeling and data analysis.
