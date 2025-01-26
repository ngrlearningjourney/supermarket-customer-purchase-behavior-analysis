# Supermarket Sales Data Analysis Portfolio 🛒

Welcome to my **Supermarket Sales Data Analysis Portfolio**! This project explores a supermarket's sales dataset, providing actionable insights to help improve business strategies and enhance customer experiences.

---

## 📂 Dataset Overview
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/arunjangir245/super-market-sales) and contains detailed transaction records, including:
- **Invoice ID**: Unique transaction identifier.
- **Branch**: Location of the transaction.
- **City**: City of the branch.
- **Customer Type**: Regular or new customer.
- **Gender**: Customer gender.
- **Product Line**: Product category.
- **Unit Price**: Price per unit.
- **Quantity**: Number of units purchased.
- **Tax 5%**: 5% tax on total cost.
- **Total**: Total transaction cost, including tax.
- **Date**: Transaction date.
- **Time**: Transaction time.
- **Payment**: Payment method used.
- **COGS**: Cost of Goods Sold.
- **Gross Margin Percentage**: Profit margin percentage.
- **Gross Income**: Total profit.
- **Rating**: Customer satisfaction rating.

---

## 🔍 Data Analysis Workflow
1. **Data Gathering**  
   Collected data from Kaggle and imported it into a data analysis environment.

2. **Data Wrangling**  
   Ensured dataset reliability by:
   - Handling missing values.
   - Verifying data formats.
   - Addressing outliers and duplicates.

3. **Exploratory Data Analysis (EDA)**  
   Analyzed each column and identified trends, patterns, and key business questions.

---

## 📊 Key Insights
### 1. Branch Performance
- **Gross Income**: Branch C leads with $5,265, while Branch A and B perform similarly.
- **Ratings**:
  - All branches share the same rating range (4–10).
  - Branch B has the lowest average rating (6.81), signaling potential dissatisfaction.

### 2. Customer Segmentation
- **Gender Distribution**:
  - Female members slightly outnumber female regular customers.
  - Male regular customers exceed male members.
- **Gender Preferences**:
  - Female customers prefer Sports and Travel.
  - Male customers favor Health and Beauty.
- **Branch-Specific Gender Trends**:
  - Branch A and B sold more products to male customers.
  - Branch C sold more products to female customers.

### 3. Product Line Analysis
- **Top-Selling Products**:
  - Members: Food and Beverages.
  - Regular Customers: Electronic Accessories.
- **Monthly Sales Highlights**:
  - Health and Beauty: March (334 items).
  - Electronic Accessories: January (333 items).
  - Home and Lifestyle: March (364 items).
  - Sports and Travel: January (375 items).
  - Food and Beverages: February (349 items).
  - Fashion Accessories: January (336 items).

### 4. Busiest Times and Seasonal Trends
- **Peak Times**:
  - Branch A & C: 10 AM.
  - Branch B: 7 PM.
- **Busiest Months**: January dominates transactions and sales across most categories.

### 5. Customer Ratings
- **Membership Ratings**:
  - Members: Average rating (6.9).
  - Regular Customers: Average rating (7).
- **Branch Ratings**: Branch B's average rating (6.81) is the lowest.

### 6. Payment Preferences
- **Members**: No strong payment preference.
- **Regular Customers**: Prefer e-wallets; credit cards are least used.

---

## 🌟 Recommendations
### 1. Branch Performance
- **Leverage Branch C’s Strategies**: Analyze and replicate successful practices from Branch C across A and B.
- **Improve Branch B Ratings**: Investigate low satisfaction scores and address issues with staff training or customer engagement.

### 2. Product Line Strategies
- **Targeted Promotions**: Use insights to design campaigns:
  - Discounts on Food and Beverages for members.
  - Deals on Electronic Accessories for regular customers.
- **Seasonal Campaigns**: Promote products based on peak months (e.g., promote Health and Beauty in March, Electronic Accessories in January)..

### 3. Customer Engagement
- **Gender-Specific Campaigns**:
  - Female-focused promotions: Sports and Travel.
  - Male-focused promotions: Health and Beauty.
- **Branch-Specific Strategies**: Tailor campaigns to customer demographics for each branch (e.g., Branch C campaigns targeting female customers).

### 4. Payment Systems
- Encourage credit card usage among regular customers with loyalty rewards or discounts.

### 5. Peak Times Optimization
- Allocate resources effectively:
  - Branch A & C: Focus on 10 AM.
  - Branch B: Focus on 7 PM.

### 6. Membership Programs
- Promote membership benefits to regular customers, emphasizing exclusive discounts or rewards.

---

## 🛠️ Tools and Technologies
- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation.
- **Matplotlib & Seaborn**: Visualization.
- **Jupyter Notebook**: Interactive analysis environment.

---
