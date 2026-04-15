**# 📊 Trader Performance vs Market Sentiment

## 🔍 Overview

This project analyzes how trader behavior and profitability vary under different market sentiment conditions (Fear, Neutral, Greed). By combining trading data with the Fear & Greed Index, the goal is to understand how psychology-driven market states influence trading outcomes.

---

## 📁 Dataset

### 1. Historical Trading Data

* Trade-level data (PnL, trade size, direction, account, timestamp)
* Used to analyze trader performance and behavior

### 2. Fear & Greed Index

* Market sentiment indicator (0–100 scale)
* Categorized into:

  * Fear
  * Neutral
  * Greed

---

## ⚙️ Methodology

### 🔹 Data Processing

* Merged trading data with sentiment data using date alignment
* Cleaned missing values and duplicates

### 🔹 Feature Engineering

* Win rate
* Number of trades
* Average trade size
* Long/short ratio
* Daily PnL aggregation

### 🔹 Analysis

* Compared trader performance across sentiment states
* Studied behavioral changes (activity, risk-taking, bias)

### 🔹 Machine Learning

* **Random Forest Classifier**

  * Predicts whether a trader-day is profitable or not
  * Achieved ~95% accuracy

### 🔹 Clustering

* **K-Means Clustering**

  * Segmented traders into 3 behavioral groups
  * Identified patterns in trading styles

---

## 📈 Key Insights

* 📌 Traders perform better during **Fear** market conditions
* 📌 Win rate remains relatively stable across sentiments
* 📌 Profit differences are driven by **trade size and behavior**, not accuracy
* 📌 Traders take **more trades and larger positions during fear**
* 📌 Strong long bias is observed during **Greed**

---

## 🤖 Models Used

* Random Forest Classifier (Supervised Learning)
* K-Means Clustering (Unsupervised Learning)

---

## 🛠 Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn

---

## 📊 Output

* Performance vs sentiment visualizations
* Behavioral analysis charts
* Predictive model results
* Trader segmentation insights

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/harshmangukiya71/Datascience_Task.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

```bash
Datascience_Task.ipynb
```

---

## 📌 Author

**Harsh Mangukiya**

* 📧 [harshmangukiya363@gmail.com](mailto:harshmangukiya363@gmail.com)
* 🔗 GitHub: https://github.com/harshmangukiya71

---
**
