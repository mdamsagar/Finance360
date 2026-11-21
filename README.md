# Finance360° — Personal Asset & Liability Tracker

**Finance360°** is a modern, self-contained personal finance and net worth balance sheet web application built for individuals who want a clear, real-time overview of their assets, liabilities, multi-currency holdings, bank loan amortization schedules, and personal lending ledgers.

Developed by **MD. APPEL MAHMUD SAGAR.**

---

## ✨ Key Features

- **5-Page Interactive Financial Workbook:**
  1. **Dashboard:** Instant overview of **Total Asset**, **Total Liability**, and **Total Equity (Net Worth)** with side-by-side Asset and Liability Summary tables.
  2. **Assets Portfolio Management:** Track Fixed Deposit Receipts, Deposit Pension Schemes, Savings/Current/RFCD Accounts, Sanchaypatra, Treasury Bonds/Bills, Prize Bonds, Mutual Funds, Investments, Shares, Crypto, Personal Lending, and Cash—complete with weighted average yield calculations, sortable columns, and interactive donut charts.
  3. **Liabilities Management:** Categorize Personal Loans, Home Loans, Auto Loans, Credit Cards, and Lending obligations with weighted average interest cost analysis.
  4. **Bank Liabilities & Loan Schedules:** Auto-generate month-by-month EMI amortization schedules, toggle installment `Paid` / `Unpaid` statuses, and automatically sync remaining principal and unaccrued interest to the Dashboard.
  5. **Non-Bank Liabilities (Personal Lenders):** Maintain a personal borrowing and repayment ledger with inline installment rows and remarks synced directly to Liabilities & Dashboard.
- **Multi-Currency Support (8 Currencies):** Switch portfolio views between **BDT (৳)**, **USD ($)**, **GBP (£)**, **EUR (€)**, **CNY (¥)**, **JPY (¥)**, **CAD (C$)**, and **INR (₹)** with customizable exchange rates.
- **Hybrid Calendar & Free-Text Date Picker:** Pick formatted dates from an interactive calendar popover or freely type custom periods (e.g., `Jan-Feb-Mar`, `Flexible`).
- **Offline-First & Multi-Format Export:** Automatically saves data locally in the browser (`localStorage`) with one-click exports for standalone **HTML**, **GitHub & Vercel ZIP**, **Windows EXE Builder**, **ISO Image**, and **Android APK Kit**.
- **Light & Dark Mode:** Clean, responsive UI styled with Tailwind CSS and Chart.js.

---

## 🚀 Quick Start & Deployment

### Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/finance360-degree.git
   cd finance360-degree
   ```
2. Open `index.html` directly in any modern web browser—no build step or backend required.

### Deploy to Vercel
1. Push the project files (`index.html`, `vercel.json`, `package.json`, `manifest.json`, `.gitignore`, and `README.md`) to your GitHub repository.
2. Go to [vercel.com](https://vercel.com), click **Add New → Project**, and import your repository.
3. Keep the default settings (Framework Preset: **Other**, Root Directory: `./`) and click **Deploy**.

---

## 🛠️ Tech Stack
- **Frontend:** HTML5, Vanilla JavaScript (ES6+)
- **Styling:** Tailwind CSS (CDN) with custom Dark/Light theme support
- **Charts:** Chart.js 4
- **Storage & Packaging:** Browser `localStorage`, PWA Web Manifest, Client-side ZIP & ISO9660 builders

---

## 📄 License
This project is created and maintained by **MD. APPEL MAHMUD SAGAR.**
