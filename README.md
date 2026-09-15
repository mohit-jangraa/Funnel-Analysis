# 📊 E-Commerce Funnel Analysis

An end-to-end **E-Commerce Funnel Analysis project** using Python and Power BI to understand customer behavior, identify conversion bottlenecks, and discover opportunities to improve the purchase journey.

---

## 🔎 Project Overview

This project analyzes customer interactions across different stages of an e-commerce journey:

**View → Add to Cart → Purchase**

The objective is to understand where customers drop off, identify high- and low-performing categories, sub-categories, brands and products, and provide actionable business insights.

The analysis was performed using **Python for data cleaning and exploratory analysis** and **Power BI for interactive dashboard visualization**.

---

## 🎯 Objectives

* Analyze the complete customer conversion funnel.
* Calculate conversion and drop-off rates at each funnel stage.
* Identify the biggest bottlenecks in the customer journey.
* Compare funnel performance across product categories.
* Analyze sub-category and brand-level performance.
* Identify high-performing and underperforming products.
* Generate actionable business recommendations.
* Build an interactive Power BI dashboard for decision-making.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook**
* **Power BI**
* **DAX**
* **Data Visualization**

---

## 📂 Project Structure

```text
Funnel-Analysis/
│
├── Notebook.ipynb
├── dashboard_funnel.pbix
├── Insights_and_conclusions.md
├── README.md
└── LICENSE
```

### Files Description

| File                          | Description                                                    |
| ----------------------------- | -------------------------------------------------------------- |
| `Notebook.ipynb`              | Data cleaning, preprocessing, funnel calculations and analysis |
| `dashboard_funnel.pbix`       | Interactive Power BI dashboard                                 |
| `Insights_and_conclusions.md` | Detailed insights, findings and business conclusions           |
| `README.md`                   | Project documentation                                          |
| `LICENSE`                     | Project license                                                |

---

## 🔄 Funnel Stages

The customer journey was analyzed through three major stages:

```text
Product View
     ↓
Add to Cart
     ↓
Purchase
```

### Key Metrics

| Metric                     |     Result |
| -------------------------- | ---------: |
| View → Cart Conversion     |  **6.19%** |
| Cart → Purchase Conversion | **49.98%** |
| View → Purchase Conversion |  **6.82%** |

These metrics help identify where customers are being lost throughout the purchase journey.

---

## 📈 Key Insights

### 1. Major Funnel Bottleneck

The **View → Cart conversion is only 6.19%**, making it the biggest bottleneck in the customer journey.

This indicates that a large number of users view products but do not proceed to add them to their cart.

### 2. Strong Cart → Purchase Performance

The **Cart → Purchase conversion is 49.98%**.

This indicates that customers who have already added a product to their cart show considerably stronger purchase intent.

### 3. Overall Conversion

The overall **View → Purchase conversion is 6.82%**, showing significant room for improvement in converting product viewers into buyers.

### 4. Category Performance

**Medicine** has the highest View → Cart conversion among the major categories at **15.79%**.

**Electronics** also performs relatively well with approximately **9.79% View → Cart conversion**.

### 5. Strong Sub-Category

**Tonometer** has the highest View → Cart conversion among the analyzed sub-categories at approximately **15.79%**.

### 6. Smartphone Performance

**Smartphone** is another strong-performing sub-category, with approximately:

* **10.69% View → Cart conversion**
* **5.77% View → Purchase conversion**

### 7. Furniture Drop-Off

Furniture has extremely high funnel drop-off, with approximately **99.86% View → Purchase drop-off**.

This indicates a significant opportunity to investigate customer behavior and product-page performance in this category.

### 8. Strong Brand Performance

The **Diamond** brand has the highest reported View → Cart conversion at approximately **33.33%**.

It also has approximately **33.33% View → Purchase conversion**.

### 9. High Product-Level Conversion

Several individual products and sub-categories show **100% conversion at specific funnel stages**.

However, these results should be interpreted carefully because they may be based on a small number of sessions.

### 10. Significant Performance Variation

Funnel performance varies substantially across:

* Categories
* Sub-categories
* Brands
* Products

This demonstrates the importance of segmentation when analyzing customer conversion.

---

## 💡 Business Recommendations

Based on the analysis, the following actions can help improve conversion:

### 🛒 Improve Product Pages

Improve product images, descriptions, pricing visibility, reviews and calls-to-action to encourage users to add products to their carts.

### 🎯 Personalized Recommendations

Use related products and personalized recommendations to increase the probability of cart additions.

### 💰 Review Pricing & Offers

Investigate high-drop-off categories and determine whether pricing, discounts or promotions could improve engagement.

### 📱 Improve User Experience

Analyze the product-view experience, especially for categories with extremely high View → Cart drop-off.

### ⭐ Learn From High Performers

Use high-performing categories, brands and products as benchmarks for improving weaker segments.

### 🔍 Investigate Low-Volume Results

Conversion rates of 100% should not automatically be considered evidence of strong performance. Minimum session thresholds should be applied before ranking products or brands.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of:

* Funnel conversion
* Funnel drop-off
* Category performance
* Sub-category performance
* Brand performance
* Product-level performance
* Conversion rates
* Customer journey analysis

### Dashboard Flow

```text
Customer Activity
       ↓
Funnel Overview
       ↓
Category Analysis
       ↓
Sub-Category Analysis
       ↓
Brand Analysis
       ↓
Product Analysis
       ↓
Business Recommendations
```

---

## 🧹 Data Preparation

The dataset was processed before performing the funnel analysis.

The preprocessing included:

* Handling missing category values.
* Handling missing brand values.
* Identifying duplicate records.
* Removing duplicate records.
* Creating funnel stages.
* Calculating conversion rates.
* Calculating drop-off rates.
* Aggregating results by category, sub-category, brand and product.

---

## 📌 Key Takeaway

> **The biggest opportunity in the funnel is improving the transition from Product View → Add to Cart.**

Although only **6.19%** of viewing sessions result in cart additions, nearly **50% of cart sessions result in purchases**.

Therefore, the primary business focus should be on improving **product discovery, product-page engagement, product presentation, pricing, recommendations and calls-to-action**.

---

## 🚀 Future Improvements

Some possible improvements to this project include:

* Add customer segmentation.
* Analyze conversion by device type.
* Analyze conversion by time/day/month.
* Perform cohort analysis.
* Analyze repeat customers.
* Add revenue and Average Order Value (AOV).
* Apply statistical significance testing.
* Add minimum-session thresholds for product/brand rankings.
* Deploy the dashboard online.
* Build automated data refresh pipelines.

---

## 👨‍💻 Author

**Mohit Jangra**

GitHub: [@mohit-jangraa](https://github.com/mohit-jangraa)

---

## 📜 License

This project is available under the license included in this repository.
