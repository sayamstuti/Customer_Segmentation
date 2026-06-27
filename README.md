# Customer_Segmentation

A comprehensive Customer Segmentation project using Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly, and Scikit-learn. This project analyzes customer purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and applies K-Means clustering to identify distinct customer segments for targeted marketing strategies and business decision-making.

---

# Table of Contents

- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering (RFM Analysis)](#feature-engineering-rfm-analysis)
- [Customer Segmentation](#customer-segmentation)
- [Cluster Profiling](#cluster-profiling)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Marketing Actions](#marketing-actions)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Author](#author)


# Overview

Customer segmentation helps businesses understand purchasing patterns and classify customers into groups based on their buying behavior.

This project performs:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering using RFM Analysis
- Data Standardization
- K-Means Clustering
- Cluster Profiling
- Business Insights and Marketing Recommendations

---

# Business Problem

Businesses often treat every customer similarly, resulting in ineffective marketing campaigns.

The objective of this project is to:

- Identify high-value customers
- Detect customers likely to churn
- Improve customer retention
- Increase customer lifetime value
- Enable personalized marketing campaigns

---

# Dataset

The dataset contains online retail transactions with features such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

### Derived Features

- Total Amount
- Recency
- Frequency
- Monetary Value

---

# Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Jupyter Notebook

---

# Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Converted Invoice Date to datetime format
- Created Total Amount feature
- Removed cancelled transactions
- Checked and treated outliers
- Converted appropriate data types

---

# Exploratory Data Analysis (EDA)

The project includes:

- Missing Value Analysis
- Distribution of Numerical Features
- Correlation Heatmap
- Top 10 Products by Revenue
- Monthly Sales Trend
- Country-wise Revenue Analysis
- Frequency vs Monetary Relationship

---

# Feature Engineering (RFM Analysis)

Three customer behavior features were created:

### Recency (R)

Number of days since the customer's last purchase.

### Frequency (F)

Number of purchases made by each customer.

### Monetary (M)

Total amount spent by each customer.

---

# Customer Segmentation

Customer segmentation was performed using **K-Means Clustering**.

### Data Scaling

StandardScaler was used before clustering.

### Optimal Number of Clusters

The Elbow Method was used to determine the optimal value of **K = 4**.

The four clusters represent:

- Regular Customers
- At-Risk Customers
- VIP Customers
- Loyal Customers

---

# Cluster Profiling

Each cluster was analyzed using average:

- Recency
- Frequency
- Monetary Value

Visualizations include:

- Cluster Profile Heatmap
- Customer Count per Cluster
- Revenue per Cluster
- Frequency vs Monetary Scatter Plot
- Recency vs Monetary Scatter Plot

---

# Key Insights

- Most revenue is generated from the United Kingdom.
- Sales peak during the festive season (November).
- A small number of products contribute significantly to overall revenue.
- Frequency has a moderate positive correlation with Monetary Value.
- VIP customers generate exceptionally high revenue despite representing a very small portion of the customer base.
- Regular customers contribute the highest overall revenue due to their large population.

---

# Business Recommendations

### VIP Customers

- Premium membership
- Exclusive discounts
- Personalized recommendations
- Early access to new products

### Loyal Customers

- Referral rewards
- Cross-selling
- Upselling
- Loyalty programs

### Regular Customers

- Personalized promotions
- Product bundles
- Email marketing campaigns

### At-Risk Customers

- Win-back campaigns
- Discount coupons
- Re-engagement emails
- Limited-time offers

---

# Marketing Actions

- Reward high-value customers through exclusive loyalty programs.
- Increase purchase frequency with personalized recommendations.
- Reactivate inactive customers using targeted discount campaigns.
- Promote complementary products through cross-selling.
- Improve customer retention with reward-based marketing strategies.

---


# How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-segmentation.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Notebook

```bash
jupyter notebook
```

Open:

```
Customer_Segmentation.ipynb
```

---

# Future Improvements

- Deploy the model as a web application.
- Automate customer segmentation using scheduled pipelines.
- Compare K-Means with DBSCAN and Hierarchical Clustering.
- Build a dashboard using Power BI or Streamlit.
- Integrate real-time customer data.

---

# Author

**Sayam Stuti Shuvadarsini**
Email:sayamstuti594@gmail.com
LinkdedIn-www.linkedin.com/in/sayam-stuti-shuvadarsini-8089b43a4



