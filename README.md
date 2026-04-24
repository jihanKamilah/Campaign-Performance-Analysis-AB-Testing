# 🚀 From Clicks to Revenue  
## What A/B Testing Taught Me About Marketing Performance  

A practical, end-to-end analysis of marketing A/B testing — not just focusing on clicks and engagement, but uncovering what actually drives **revenue and profit**.

---

## 🧩 Background

In digital marketing, success is often measured by metrics like CTR, impressions, and engagement.  
And when those numbers go up, it’s easy to assume the campaign is performing better.

But in reality, these are often just **vanity metrics**.

A campaign can attract more clicks, generate more traffic, and still fail to deliver real business value.

This is where many decisions become risky:
- Scaling budget based on misleading signals  
- Replacing stable campaigns too quickly  
- Optimizing for attention instead of outcomes  

This project was built to challenge that assumption.

Instead of asking *“Which campaign gets more clicks?”*,  
the focus shifts to a more important question:

> **Which campaign actually drives better business results?**

---

## 📊 Project Overview

At first glance, the Test Campaign looks like a clear winner:

- Higher CTR  
- More clicks  
- Better engagement  

But the real question is:

> **Does it actually generate more money — or just better-looking metrics?**

This project answers that by analyzing the **full funnel performance** and connecting it to **real business outcomes**.

---

## 🎯 Objectives

- Compare **Control vs Test Campaign**
- Evaluate performance across:
  - Funnel metrics (CTR → Purchase)
  - Conversion rates
  - Revenue & profit
  - ROI & CAC
- Validate results using **statistical testing**
- Provide **data-driven business recommendations**

---

## 🧰 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels (Z-test)

---

## 🗂️ Dataset

The dataset consists of two campaign groups:
- `control_group.csv`
- `test_group.csv`

Each dataset includes:
- Impressions, clicks, and engagement metrics  
- Funnel stages (view → cart → purchase)  
- Marketing spend  

---

## 🔧 Data Preparation

Key steps:
- Merging datasets (Control + Test)
- Standardizing column names
- Handling missing values
- Converting date formats

---

## ⚙️ Feature Engineering

### Funnel Metrics
- CTR  
- View Rate  
- Cart Rate  
- Purchase Rate  

### Financial Metrics
- Revenue (assumed AOV = 50)  
- Profit  
- CAC (Customer Acquisition Cost)  
- ROI  

---

## 🔍 Key Analyses

### 1. Funnel Analysis
- Test Campaign performs better at the top (CTR ↑)
- Major drop-off at **mid-funnel (view → cart)**

---

### 2. Conversion Analysis
- Higher purchase rate in Test Campaign  
- Indicates **higher intent users**

---

### 3. Statistical Testing
- Z-test confirms results are **statistically significant**
- Improvement is not due to random chance

---

### 4. Revenue & Profit
- Test Campaign generates:
  - Higher revenue  
  - Higher profit  

---

### 5. Efficiency Metrics
- Control Campaign:
  - Lower CAC  
  - Higher ROI  
  - Faster break-even  

---

### 6. Scenario & What-if Analysis
- Test Campaign consistently wins across:
  - Pessimistic  
  - Realistic  
  - Optimistic scenarios  

---

### 7. Funnel Bottleneck
Biggest issue:
> **View Content → Add to Cart**

This is the highest-impact improvement opportunity.

---

## 💡 Key Insights

- Test Campaign = **better for scale & profit**
- Control Campaign = **better for efficiency**

Trade-off:
> Scale vs Cost Efficiency

---

## 🧭 Final Recommendation

Instead of choosing one:

### ✅ Scale the Test Campaign (Strategically)
- Proven to generate higher profit  
- Strong under different scenarios  

---

### 🔧 Fix Mid-Funnel Bottleneck (High Priority)
Focus on improving:
- Product page experience  
- Pricing perception  
- UX friction  
- Alignment between ads and landing page  

---

### 📏 Monitor CAC & ROI
Set guardrails:
- Maximum acceptable CAC  
- Minimum ROI threshold  

---

### 🎯 Leverage High-Performing Segments
- High-reach users  
- Weekend traffic  

---

### ⚖️ Keep Control Campaign as Benchmark
- Maintain efficiency baseline  
- Consider hybrid budget strategy  

---

## 🧠 What I Learned

> **Better metrics don’t always mean better outcomes.**

CTR and engagement can be misleading —  
real performance comes from:
- Profit  
- Efficiency  
- Scalability  

---

## ▶️ How to Use

1. Open the notebook `ab_testing_analysis.ipynb`  
2. Run all cells step by step  
3. Explore:
   - Funnel analysis  
   - Conversion rates  
   - Revenue & profit insights  
   - Scenario simulations  

---

## 📈 Output

The analysis provides:
- Funnel comparison (Control vs Test)
- Conversion rate breakdown
- Revenue, profit, and ROI insights
- Statistical validation (Z-test)
- Scenario & what-if analysis

---

## 📎 Notes

- AOV is assumed to be **50 USD**
- Results are based on aggregated campaign data
- This project focuses on **analytical thinking & business insight**, not just modeling

---

## ✨ Author

**Jihan Kamilah**  
Data Analyst | Turning data into meaningful insights  

- GitHub: https://github.com/jihanKamilah  
- Medium: https://medium.com/@jihankamilah
