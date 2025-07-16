# 🎉 UPI Transactions Dashboard

![Power BI](https://img.shields.io/badge/PowerBI-Data%20Visualization-blue) ![DAX](https://img.shields.io/badge/DAX-Calculations-orange) ![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

## 🔗 Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Data Source](#data-source)
4. [Screenshots](#screenshots)

---

## 🚀 Project Overview

This Power BI report provides an interactive analysis of UPI transaction data across multiple banks and cities.  
Key insights include:

- **Monthly Remaining Balance** trends (line & area chart)  
- **Transaction Amounts** by City, Bank (sent/received), Device Type, Gender, Age Group, Payment Method, Purpose, and Transaction Type  
- **Drill‑through** from summary visuals down to transaction‑level details  

You can slice and dice the data in real‑time to answer questions like:  
> *“Which bank saw the highest outgoing volume in Bangalore in Q2?”*  

---

## 📊 Features

* **Dynamic Slicers**: Bank (Sent / Received), City, Gender, Age Group, Device, Merchant, Payment Method, Purpose, Transaction Type, Status (Success/Fail)
* **Time‑Series Analysis**

  * Animated line + area chart of **Remaining Balance** by Month
  * Month‑over‑Month % change measures (DAX)
* **Matrix Breakout**: Amount vs. Remaining Balance by City & Month
* **Custom DAX Measures**:

  * Total Amount
  * Total Remaining Balance
  * % Growth, Failure Rate
* **Responsive Layout**: Optimized for desktop + tablet
* **Polished UX**: Consistent color theme, tooltips, and drill‑through details

---

## 📂 Data Source

| Column Name        | Description                       |
| ------------------ | --------------------------------- |
| `TransactionID`    | Unique transaction identifier     |
| `TransactionDate`  | Date & time of the transaction    |
| `Amount`           | Transaction amount (INR)          |
| `RemainingBalance` | Account balance after transaction |
| `BankNameSent`     | Sending bank name                 |
| `BankNameReceived` | Receiving bank name               |
| `City`             | Transaction location              |
| `Gender`           | Customer gender                   |
| `AgeGroup`         | Customer age bracket              |
| `DeviceType`       | Mobile / Desktop / Tablet         |
| `PaymentMethod`    | UPI App / QR / USSD               |
| `PaymentMode`      | Online / Offline                  |
| `MerchantName`     | Payee merchant                    |
| `Purpose`          | Transaction purpose/category      |
| `TransactionType`  | Debit / Credit                    |
| `Status`           | Success / Fail                    |
| `Currency`         | Currency code (e.g. INR)          |

Source CSV: `/data/upi_transactions.csv`

---

## 🚩 Screenshots

<img width="1419" height="780" alt="image" src="https://github.com/user-attachments/assets/d8451037-2abd-460d-8292-94f130b93362" />
<img width="1420" height="766" alt="image" src="https://github.com/user-attachments/assets/c5b17af2-95f9-46ba-aa93-dedca48b1333" />


---
---

