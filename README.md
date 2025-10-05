# Finance Dashboard

A simple **Finance Dashboard** that serves as a central hub for three useful finance tools:

1. **PocketSave** — Track income, expenses, and savings goals.  
2. **Loan Helper** — Calculate loans and view amortization schedules.  
3. **EMI Calculator** — Compute monthly EMI, total interest, and total payment.

All apps run **locally in the browser** and do not require any backend or API keys (except the FRED API demo in PocketSave, which is optional).

---

## Features

### PocketSave
- Add income and expense transactions.
- Track your current balance, total income, and total expenses.
- Set and track savings goals.
- Mini chart to visualize recent transactions.
- Local storage support (data persists in browser).

### Loan Helper
- Calculate loan payments with custom principal, interest, and term.
- Support for different payment frequencies (Monthly, Bi-weekly, Weekly, Yearly).
- Toggleable amortization schedule (first 100 rows shown).
- Results update live.

### EMI Calculator
- Calculate monthly EMI, total interest, and total payment.
- Supports tenure in years or months.
- Interactive doughnut chart showing principal vs interest.
- Reset functionality for quick recalculation.

---

## Installation

1. Clone or download this repository.
2. Make sure all files (`index.html`, `savings.html`, `loan.html`, `emi.html`) are in the same folder.
3. Open `index.html` in your preferred browser.

---

## Usage

1. Open **index.html** to view the dashboard.
2. Click on any app card's **"Open App"** button to navigate to that tool.
3. Use each app as follows:
   - **PocketSave:** Add transactions and set savings goals.
   - **Loan Helper:** Enter loan details and calculate payments.
   - **EMI Calculator:** Enter loan amount, interest rate, and tenure to compute EMI.

---

## Tech Stack

- **HTML5, CSS3, JavaScript**
- Local storage for PocketSave transactions
- Chart.js for EMI and PocketSave charts

---

## License

This project is open-source and free to use for personal and educational purposes.

---

Made with ♥ by [Tech Coders]

---

1. Team Name: **Tech Coders**
2. Team Members Name:
            - **Chaitanya Shinde**
            - **Shardul Rane**
            - **Yash Salvi**
            - **Prasann Kudale**
3. Project Name: **Finance Dashboard**
4. Project Abstract:
      Managing personal finances can be complex and scattered across multiple tools, making it difficult for users to track  savings, loans, and EMIs efficiently. The Finance Dashboard is a web-based solution that unifies these functionalities into a single, easy-to-use platform.

The application consists of three integrated modules:

   1.**PocketSave** – Track income, expenses, and set savings goals.

   2.**Loan Helper** – Calculate loan payments and generate amortization schedules.

   3.**EMI Calculator** – Compute monthly EMI, total interest, and total payment with visual charts.

All data is stored locally in the browser, ensuring privacy and security, while JavaScript and Chart.js provide real-time calculations and interactive visualizations. The Finance Dashboard empowers users to manage their finances efficiently, plan budgets, and make informed financial decisions, all within a single platform.

5. Tech Stack:
   **Frontend**:
      -HTML5 & CSS3 – Structure and styling of the web app
      -JavaScript – Logic for calculations, transactions, and interactivity

   **Data & Storage**:
      -Local Storage – Store user transactions and savings goals securely in the browser

   **Visualization**:
      -Chart.js – Display charts for savings, loan amortization, and EMI breakdowns

   **Tools & Environment**:
      -Web Browser – Runs entirely client-side, no backend required
      -Code Editor – VS Code or any preferred editor

6. Dataset Used:
      -**PocketSave:** No external dataset; all transactions and savings goals are stored locally in the browser.
      -**Loan Helper & EMI Calculator:** No external dataset; calculations are based on user-input values (loan amount, interest rate, tenure, etc.).

