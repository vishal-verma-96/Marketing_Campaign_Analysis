# 📊 Customer Campaign Response Analysis

This project explores customer response patterns to marketing campaigns using the **4Ps of Marketing** — Product, Price, Place, and Promotion. The dataset includes customer demographics, purchase behavior, and campaign engagement, providing insights into how different customer segments respond to various marketing efforts.

---

## 📝 Description

This analysis focuses on:
- Segmenting customers based on age, income, education, and family structure.
- Visualizing spending patterns across product categories.
- Investigating the effectiveness of marketing campaigns.
- Testing hypotheses (e.g., Do customers with kids prefer online shopping?).

Using **Seaborn** and **Plotly**, interactive and static visualizations reveal how customer demographics influence marketing campaign acceptance.

---

## 📂 Project Structure

- 📁 **marketing-campaign-analysis/**
  - 📄 `marketing_data.csv` 
  - 📄 `analysis.ipynb` 
  - 📁 **images/** 
    - 📊 `income_spending_product.png`
    - 📊 `age_response_pattern.png`
    - 📊 `customer_acceptance.png`
    - 📊 `spending_vs_household.png`
    - 📊 `sales_distribution.png`
    - 📊 `education_complaint_customer.png`
  - 📄 `README.md` (You 🫵 are here!)

---

## 📥 Dataset Features Description:

| Variable              |	                                         Description                                        |
|-----------------------|---------------------------------------------------------------------------------------------|
| ID                    | Customer's unique identifier                                 |
|Year_Birth             |	Customer's birth year                                        |
| Education	            | Customer's education level                                   |
| Marital_Status        | Customer's marital status                                    |
| Income                | Customer's yearly household income                           |
| Kidhome               | number of small children in customer's household number of teenagers in customer's household |
| Teenhome              | Number of teenagers in customer's house                       |
| Dt_Customer           | Date of customer's enrollment with the company                |
| Recency               | Number of days since the last purchase                        |
| MntWines              | Amount spent on wine in last 2 years                          |
| MntFruits             | Amount spent on fruits in last 2 years                        |
| MntMeatProducts       | Amount spent on meat products in last 2 years                 |
| MntFishProducts       | Amount spent on fish products in last 2 years                 |
| MntSweetProducts      | Amount spent on sweet products in last 2 years                |
| MntGoldProds          | Amount spent on gold in last 2 years                          |
| NumDealsPurchases     | Number of purchases made with discount                        |
| NumWebPurchases       | Number of purchases made through company's website            |
| NumCatalogPurchases   | Number of purchases made using catalog                        |
| NumStorePurchases     | Number of purchases made directly in store                    |
| NumWebVisitsMonth     | Number of visits to company's website in the last month       |
| AcceptedCmp1          | 1 if the customer accepted the 1st campaign, 0 otherwise      |
| AcceptedCmp2          | 1 if the customer accepted the 2nd campaign, 0 otherwise      |
| AcceptedCmp3          | 1 if the customer accepted the 3rd campaign, 0 otherwise      |
| AcceptedCmp4          | 1 if the customer accepted the 4th campaign, 0 otherwise      |
| AcceptedCmp5          | 1 if the customer accepted the 5th campaign, 0 otherwise      |
| Response              | 1 if the customer accepted the last campaign, 0 otherwise     |
| Complain              | 1 if customer complained in the last 2 years                  |
| Country               | Customer's location                                           |

and the dataset already in the current repository.
---

## 📊 Sample Visualization

### 🎯 Age Group vs Campaign Response Proportion

![Age Group vs Response](images/age_response_plot.png)

---

## 🔧 Technologies Used

- Python
- Pandas
- Seaborn
- Plotly
- Matplotlib
- Scipy (for hypothesis testing)

---

## 📌 Key Insights

- Majority of customers are middle-aged to older adults
- Highest selling product is *Wine*
- Highest age group accepted campaign are $25-34$.
- Spending tends to decrease as the number of children increases.
- Majority of the individuals preffered offline shopping

## 📈 Hypotheses Tested

- H1: Older people are not as tech-savvy and prefer shopping in-store. ✅
- H2: Customers with kids prefer to shop online. ❌
- H3: Other channels cannibalize store purchases. ❌
- H4: US fares significantly better than the rest of the world in total purchases.❌

## 🙌 Author

**Vishal Verma**<br/>
🔎 Passionate about Data Visualization, Data Science, and Artificial Intelligence<br/>
📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/vishalds/)

## ⭐ Final Note

> This project offers a hands-on approach to learning data analysis while uncovering valuable insights from real-world marketing data.

If you enjoyed this project, consider giving it a ⭐.
