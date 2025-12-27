# AtliQ Hospitality Revenue Analysis

## 📌 Project Overview
This project provides a comprehensive analysis of revenue, occupancy, and ratings for AtliQ Hospitality. The goal is to provide stakeholders with actionable insights into property performance, city-wise trends, and booking channel efficiency to drive data-driven decision-making.

---

## 🛠️ DAX Measures & Logic
The following key measures were developed to track Weekly performance:

* **Selected Week (`selv`)**: Identifies the selected week number; if none is selected, it defaults to the latest available week in the dataset.
* **Current Week Revenue (`revcw`)**: Calculates the total revenue generated for the currently filtered/selected week.
* **Previous Week Revenue (`revpw`)**: Uses `FILTER` and `ALL` functions to bypass existing filters and calculate revenue for the prior week (Week - 1).
* **Wow % Change**: Calculated using the `DIVIDE` function to find the percentage variance between `revcw` and `revpw`, with a safe fallback of 0 for zero-division cases.

---

## 📸 Dashboard Preview
![Main Dashboard](INSERT_YOUR_IMAGE_LINK_HERE)
> **Tip:** Replace the placeholder above with your high-resolution screenshot showing KPI cards and city-wise performance.

---

## 🚀 Key Strategic Insights

### 1. Market Dominance
* **Mumbai** is the primary revenue driver, generating approximately **$669M**.
* **Bangalore** and **Hyderabad** follow as key secondary markets.

### 2. Property Performance
* **AtliQ Exotica** is the top-performing property by revenue.
* Current average rating for top properties stands at **3.62**, indicating a significant opportunity for service improvement to drive future retention.

### 3. Channel & Satisfaction Trends
* **Booking Channels:** "Direct Webpage" and major third-party platforms are the most efficient revenue streams.
* **Customer Satisfaction:** **Delhi** consistently outperforms other cities in both occupancy rates and guest ratings, serving as the operational benchmark for the group.

---

## 📂 How to Use
1. Clone this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the **Week Filter** to toggle between different time periods.
4. Hover over city charts to see granular property-level breakdowns.
