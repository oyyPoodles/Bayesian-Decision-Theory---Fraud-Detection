# 🧠 Bayesian Decision Theory for Fraud Detection in Credit Card Transactions

## 📝 Project Overview
This project implements **Bayesian Decision Theory** to classify credit card transactions as fraudulent or legitimate. By leveraging probabilistic decision boundaries, the system helps financial institutions minimize fraud risk while balancing false positives and false negatives based on financial impact.

---

## 🎯 Problem Statement
Financial fraud costs businesses billions annually. This project aims to:

- ✅ Detect fraudulent transactions with high accuracy  
- ✅ Minimize financial losses by optimizing the trade-off between false positives and false negatives  
- ✅ Provide a probabilistic framework for risk assessment  

---

## 📌 Use Case: FinTech & Banking Fraud Detection

### Industry Applications:
- 🏦 Payment processors  
- 💳 Digital banking platforms  
- 🛍️ E-commerce fraud prevention systems  

### Why Bayesian Decision Theory?
- 🔍 Incorporates prior knowledge of fraud patterns  
- 📊 Quantifies risk through probabilistic classification  
- 💸 Allows cost-sensitive decision making based on financial impact  
- 🧾 Provides interpretable results for fraud analysts  

---

## 📂 Dataset
The project uses a comprehensive credit card transaction dataset with:
- 📈 **1.3 million** transactions (training set)  
- 📉 **555,719** transactions (test set)  
- 📋 **11 features** including transaction amount, merchant location, and cardholder demographics  
- ⚠️ **Highly imbalanced** classes (fraud rate ~0.58%)  

---

## 🔧 Technical Implementation

### Key Steps:
1. **Data Preprocessing**
   - Feature selection and encoding  
   - Standardization of numerical features  
   - Handling class imbalance

2. **Bayesian Modeling**
   - Computes class-conditional probabilities using Gaussian distributions  
   - Implements log-likelihood functions for efficient computation  
   - Estimates prior probabilities from training data

3. **Decision Making**
   - Applies Bayesian decision boundaries  
   - Can incorporate custom loss functions for cost-sensitive classification  

### Technologies Used:
- 🐍 Python  
- 🔥 PyTorch (for tensor operations)  
- 📦 Scikit-learn (for preprocessing)  
- 🐼 Pandas / 🧮 NumPy (data manipulation)  

---

## 🚀 How to Use

1. **Clone the repository**
```bash
git clone https://github.com/your-username/Bayesian-Decision-Theory-Implementation-For-Fraud-Detection.git
