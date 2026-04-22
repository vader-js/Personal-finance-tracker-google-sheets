# Personal-finance-tracker-google-sheets
A personal finance tracking system developed in Google Sheets that automates transaction logging, balance calculations, and financial summaries. The tracker uses advanced spreadsheet formulas and interactive dashboards to help users understand spending patterns and income trends.
---

## ✨ Features
- Automatic running balance calculation
- Income and expense tracking
- Customizable categories
- Interactive dashboard with charts and summaries
- Clean separation of data entry and analytics
- Beginner-friendly, no manual calculations required

---

## 🗂 Sheet Structure

### 1️⃣ Status Tab
Used for configuration and setup.

- Starting balance
- Income categories
- Expense categories

> ⚠️ Changes here automatically reflect across the entire tracker.

📸 **Screenshot:**  
`![Status Tab](screenshots/status-tab.png)`

---

### 2️⃣ Transactions Tab
This is where all financial activity is recorded.

**Editable columns:**
- Date (calendar picker)
- Transaction (description)
- Amount
- Category (dropdown)

**Auto-generated columns (do not edit):**
- Type (Income / Expense)
- Running Balance

📸 **Screenshot:**  
`![Transactions Tab](screenshots/transactions-tab.png)`

---

### 3️⃣ Dashboard Tab
Provides a visual summary of your finances.

Includes:
- Current balance
- Income vs Expense pie chart
- Category breakdowns
- Aggregated monthly insights

All visuals update automatically based on transaction data.

📸 **Screenshot:**  
`![Dashboard](screenshots/dashboard.png)`

---

## 🧭 How to Use
1. Update your **Starting Balance** in the **Status** tab
2. Customize income and expense categories (optional)
3. Add transactions in the **Transactions** tab
4. View insights and summaries in the **Dashboard**

---

## 🧠 Behind the Scenes
This tracker uses advanced spreadsheet logic, including:
- `ARRAYFORMULA`
- `SCAN` for running balances
- Data validation (dropdowns)
- Dynamic aggregations for dashboards

No scripting required.

---

## 📂 Template Access

- 📄 **Google Sheets Template (Make a Copy):**  
  👉 *[Insert Google Sheets copy link here]*

- 📥 **Excel Template:**  
  Available in the `/templates` folder of this repository.

---

## 🔒 Data Safety
This repository contains **no personal financial data**.  
All shared files use **sample values only**.

---

## 🚀 Future Improvements
- Budget limits per category
- Monthly comparisons
- Forecasting and trend analysis
- Python or BI tool integration

---

## 👤 Author
**Ayomide**  
Software Engineer | Data & Analytics Enthusiast

---

> Built to simplify financial tracking and improve financial awareness.
