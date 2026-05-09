# 🛍 Customer Segmentation using K-Means Clustering

A machine learning project that groups customers into different segments based on their purchasing behavior using the K-Means Clustering algorithm. This helps businesses understand customer patterns and improve marketing strategies.

---

# 📌 Project Overview

This project uses unsupervised machine learning to analyze customer data and divide them into meaningful groups based on:

- Annual Income
- Spending Score

It helps identify:
- High-value customers
- Low-spending customers
- Target groups for marketing

---

# 🗂 Dataset

Dataset Used: Mall Customers Dataset

Available on Kaggle:
https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

### Dataset Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

# ⚙ Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# 🚀 Project Workflow

## 1. Data Loading
Load dataset from CSV file.

## 2. Data Preprocessing
- Check missing values
- Select important features
- Normalize data using StandardScaler

## 3. Finding Optimal Clusters
Use **Elbow Method** to find best value of K.

## 4. K-Means Clustering
Apply K-Means algorithm to group customers.

## 5. Visualization
Plot customer clusters using scatter plots.

## 6. Cluster Analysis
Understand behavior of each segment.

---

# 📊 Visualizations

- Elbow Method Graph
- Customer Segmentation Scatter Plot
- Cluster Centers Visualization

---

# 📈 Machine Learning Algorithm

## K-Means Clustering

K-Means groups data into clusters based on similarity.

Used features:
- Annual Income
- Spending Score

---

# 🖥 How to Run

## Step 1: Install Requirements

```bash
pip install pandas numpy matplotlib scikit-learn

