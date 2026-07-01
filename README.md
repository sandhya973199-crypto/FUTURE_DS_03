# Bank Marketing Campaign - Funnel & Channel Performance Analysis

## 📊 Project Overview
This project focuses on analyzing data from a bank's direct marketing campaigns to evaluate conversion performance. The analysis is structured into two main components: a **Campaign Conversion Funnel** detailing customer progression through specific marketing stages, and a **Channel Performance Analysis** measuring the conversion efficiency of different contact methods.

---

## 📈 Key Metrics & Funnel Performance

### 1. Conversion Funnel Summary
The campaign funnel tracks progression from initial contact to a successful subscription decision (`yes`).

| Funnel Stage | Total Count | Stage Conversion Rate | Drop-off Rate |
| :--- | :---: | :---: | :---: |
| **Total Customers Contacted** | 45,211 | 100.0% | 0.0% |
| **Subscribers (Outcome: Yes)** | 5,289 | 11.7% | 88.3% |

* **Overall Funnel Insights:** Out of 45,211 targeted prospects, 5,289 individuals successfully subscribed to the term deposit, resulting in an overall baseline conversion rate of **11.7%**.

---

## ☎️ Channel Performance Analysis
Using a Pivot Table breakdown, conversion outcomes were isolated by communication channel (`contact`) to identify the most effective outreach methods:

### Channel Breakdown Grid
* **Cellular:** 4,369 conversions out of 29,285 contacts ➡️ **14.9% Conversion Rate**
* **Telephone:** 390 conversions out of 2,906 contacts ➡️ **13.4% Conversion Rate**
* **Unknown:** 530 conversions out of 13,020 contacts ➡️ **4.1% Conversion Rate**
* **Grand Total:** 5,289 conversions out of 45,211 contacts ➡️ **11.7% Average Conversion Rate**

### 🧠 Analytical Insights & Recommendations
1. **Prioritize Cellular Outreach:** Cellular communication represents the highest-performing channel with a **14.9%** conversion rate. It also accounts for the vast majority of successful acquisitions (4,369 out of 5,289 total conversions).
2. **Address the "Unknown" Gap:** Prospects categorized under the "Unknown" contact method yielded an incredibly poor conversion rate of just **4.1%**, while representing a massive chunk of data (13,020 contacts). Standardizing data collection to eliminate "unknown" labels will significantly reduce wasted marketing spend.
3. **Optimized Resource Allocation:** Future marketing budgets should heavily favor automated and personalized cellular campaigns, as they deliver over 3x the efficiency of unclassified data channels.

---

## 📂 Repository Contents
* **`FUTURE_DS_03.xlsx`**: The finalized Excel workbook containing:
  * `SUMMARY DASHBOARD`: High-level funnel metrics table and horizontal bar chart visualization.
  * `CHANNEL ANALYSIS`: Pivot Table detailing contact channels with calculated conversion percentages.
  * `bank-full`: The cleaned, raw source data.
* **`README.md`**: Technical report and performance summary (this file).

---

## 🛠️ Tools Used
* **WPS Spreadsheet / Microsoft Excel**: Data cleaning, Pivot Table creation, and formula-driven analysis (`COUNTA`, percentage distribution modeling).
* **Data Visualization**: Horizontal Bar Charting for intuitive funnel tracking.
