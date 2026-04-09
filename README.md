# Online Retail Analysis

## Project Overview
This project analyses customer purchasing behaviour in an online retail dataset to uncover insights that can drive business growth.

The analysis focuses on:
- Identifying key customers
- Understanding product demand
- Exploring differences across countries
- Highlighting international growth opportunities

---

## Business Objectives
The main goals of this project are to:
- Identify high-value customers
- Analyse top-performing products
- Understand geographic sales distribution
- Provide data-driven business recommendations

---

## Dataset
- Over 500,000 transactions
- Key features:
  - CustomerID
  - Description
  - Quantity
  - UnitPrice
  - Country
  - InvoiceDate

---

## Data Cleaning
To ensure accurate analysis:
- Removed missing CustomerID
- Removed negative or zero Quantity
- Removed negative or zero UnitPrice

---

## Feature Engineering
Created a key metric:

```
TOTAL_SALES = Quantity × UnitPrice
```

This metric is used to measure revenue and customer value.

---

## Key Insights

### Product Analysis
- Top products are mainly decorative and gift items
- Common keywords:
  - Vintage
  - Heart
  - Set
  - Pink

Indicates strong demand for home décor products.

---

### Sales by Country
- The United Kingdom dominates sales
- Strong international markets:
  - Netherlands
  - EIRE (Ireland)
  - Germany
  - France

International markets contribute meaningful revenue.

---

### Customer Insights
- A small number of customers generate most of the revenue

Follows the Pareto Principle (80/20 rule).

---

### Non-UK Market Opportunities
After excluding the UK:
- Top markets:
  - Netherlands
  - EIRE
  - Germany

Key targets for expansion.

---

### Customer Behaviour
- High-spend markets:
  - EIRE
  - Netherlands
  - Singapore

- High-volume markets:
  - Netherlands
  - EIRE

Suggests the presence of bulk or wholesale buyers.

---

### Price Sensitivity
- Higher price tolerance in:
  - Singapore
  - Lebanon

Pricing strategies should vary by region.

---

### Market Segmentation
Markets can be grouped as:
- High Volume + High Value → Wholesale markets
- Low Volume + High Value → Premium markets
- Low Volume + Low Value → Emerging markets

---

## Visualisations
The project includes:
- Sales by country charts
- Top customers analysis
- Market segmentation analysis
- Product demand analysis

---

## Business Recommendations
- Expand into high-value markets:
  - Netherlands
  - EIRE
  - Singapore
- Focus on high-value customers with loyalty strategies
- Prioritise décor and gift product categories
- Implement country-specific pricing strategies
- Use data-driven decision making for growth

---

## Conclusion
While the UK dominates current sales, the real growth opportunity lies in:
- International expansion
- Customer segmentation
- Targeted marketing strategies

---

## Tools and Technologies
- R
- data.table
- ggplot2

---

## Final Insight
Future growth lies in understanding customers and expanding into high-value global markets.
