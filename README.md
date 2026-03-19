# 🛒 Online Retail Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20Online%20Retail%20II-green)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

An exploratory data analysis (EDA) project analyzing transactional data from a 
UK-based online retailer. The goal was to uncover patterns in revenue, product 
performance, customer behavior, and geographic distribution using Python.

---

## 📌 Project Overview

This project was completed as part of building my data analytics portfolio. 
I worked with the Online Retail II dataset from the UCI Machine Learning 
Repository, which contains 1M+ transactions from 2009–2011. The notebook 
in this repository uses a 100-row sample to keep the repo lightweight, but 
all code is fully compatible with the complete dataset.

---

## ❓ Business Questions Explored

- How has revenue trended over time?
- Which products drive the most sales?
- Where are customers located outside the UK?
- How many customers are repeat buyers vs. one-time?
- What data quality issues exist in raw transactional data?
- What does the distribution of transaction values look like?
- How large are typical customer orders (basket size)?

---

## 📊 Key Findings

- **Revenue** is concentrated on a small number of days and products — 
  the Victorian Sewing Box Large was the single highest revenue item in 
  the sample by a significant margin
- **Transaction values** are heavily right-skewed, with most orders under 
  £20 but occasional bulk orders pushing up to £350+
- **Basket sizes** follow a similar pattern — most invoices contain fewer 
  than 50 units, but a handful of outlier orders reach 300–450+ units, 
  likely from wholesale bulk buyers
- **Geographic distribution** in this sample is limited to the UK and France, 
  but the full dataset shows the Netherlands, EIRE, and Germany as the 
  strongest international markets
- **28.6% of customers** made repeat purchases in this sample, suggesting 
  the business leans heavily on new customer acquisition

---

## 🗂️ Project Structure
```
online-retail-eda/
├── eda_online_retail.ipynb   # Main analysis notebook
├── data/
│   └── online_retail_II.xlsx # 100-row sample dataset
├── images/
│   ├── top_products.png
│   ├── totalprice_distribution.png
│   ├── basket_size.png
│   ├── top_countries.png
│   └── customer_behavior.png
├── requirements.txt
└── README.md
```

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python 3 | Core programming language |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| Seaborn | Statistical plotting |
| Jupyter Notebook | Interactive development environment |
| openpyxl | Reading Excel files |

---

## 🚀 How to Run This Project

1. **Clone the repository**
```bash
   git clone https://github.com/robillarddylan5/online-retail-eda.git
   cd online-retail-eda
```

2. **Install dependencies**
```bash
   pip install -r requirements.txt
```

3. **Download the full dataset** *(optional — sample already included)*  
   The complete dataset can be downloaded from the 
   [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/502/online+retail+ii).
   Place it at `data/online_retail_II.xlsx` and update the sheet name in 
   the notebook if needed.

4. **Open the notebook**
```bash
   jupyter notebook eda_online_retail.ipynb
```

5. **Run all cells**  
   Use **Kernel → Restart & Run All** to execute the full analysis from top 
   to bottom.

---

## ⚠️ Notes on the Sample Dataset

This repository uses a 100-row sample of the full dataset to keep file sizes 
manageable for GitHub. As a result, some visualizations (like the monthly 
revenue chart and geographic breakdown) reflect the limitations of the sample 
rather than the full dataset. All code is written to scale — running it against 
the complete 1M+ row dataset will produce fully populated charts and more 
statistically meaningful results.

---

## 📁 Dataset Source

**Online Retail II**  
UCI Machine Learning Repository  
[https://archive.ics.uci.edu/dataset/502/online+retail+ii](https://archive.ics.uci.edu/dataset/502/online+retail+ii)

> This dataset contains all transactions for a UK-based online retailer 
> between December 2009 and December 2011. The company primarily sells 
> unique all-occasion giftware, and many customers are wholesalers.

---

## 👤 Author

**Dylan Robillard**  
[github.com/robillarddylan5](https://github.com/robillarddylan5)
```


