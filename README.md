# 🏠 Chennai Rental Market Analysis

## 📌 Project Overview

This project analyzes the Chennai residential rental market using rental property data to identify pricing patterns, locality-level differences, property characteristics, and rental affordability.

The analysis was designed to help renters understand rental prices across Chennai and identify areas that may offer better rental value.

---

## 🎯 Business Objective

The main objective of this project is to analyze Chennai rental listings and answer questions such as:

- What is the average and median rent in Chennai?
- Which localities have the highest rental prices?
- Which localities have relatively affordable rental options?
- How does rent vary by BHK?
- Does property size influence rental price?
- How does furnishing status affect rent?
- Which localities have higher rent per square foot?

---

## 📊 Dataset

The project uses the **House Rent Dataset** containing rental property listings from Indian cities.

For this project, the data was filtered to focus specifically on **Chennai**.

### Final dataset

- Original records: 4,746
- Chennai records: 891
- Final records after data cleaning: 890

### Important fields

- Posted On
- BHK
- Rent
- Size
- Floor
- Area Type
- Area Locality
- City
- Furnishing Status
- Tenant Preferred
- Bathroom
- Point of Contact

---

## 🧹 Data Cleaning

The dataset was cleaned using Microsoft Excel.

The following steps were performed:

- Filtered the dataset to Chennai
- Checked for missing values
- Checked for duplicate records
- Verified data types
- Standardized inconsistent locality names
- Removed one invalid record where the locality field contained a numeric value
- Reviewed extreme rent and property-size values
- Preserved unusual rental values where there was no sufficient evidence that they were data errors

The final dataset contains **890 Chennai rental listings**.

---

## 🧮 Calculated Metrics

The following analytical metric was created in Power BI:

### Rent per Square Foot

```text
Rent per Sq Ft = Monthly Rent / Property Size
