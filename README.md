# 📱 Bankist – Minimalist Banking Web App

**Bankist** is a fictional international banking application built using **vanilla JavaScript**, with a minimalist design approach. It simulates a real-world banking experience, allowing users to log in, view transactions, transfer money, request loans, and more – all handled on the frontend.

---

## 🚀 Features

- **Secure Login System** using username and PIN
- **Transaction History** with contextual date formatting (e.g. “Today”, “2 days ago”)
- **International Currency & Date Formatting** based on user locale
- **Transfers** between accounts with balance validation
- **Loan Requests** based on deposit history
- **Account Closure** with confirmation
- **Auto Logout Timer** for session security
- **Sorted Transactions** view toggle
- **Real-Time UI Updates** after every action
- **Dynamic Username Generation** from full name

---

## 🧑‍💻 Live Demo
[Try Now](https://shubhAgrawal666.github.io/Bankist/)

---

## 🛠️ Tech Stack

- 💡 **JavaScript (ES6+)**
- 🎨 Minimalist UI using **HTML5 + CSS3**
- 🗂 **Intl API** for currency and date localization

---

## 📂 File Structure

```
📁 Bankist/
 ┣ 📄 index.html
 ┣ 📄 style.css
 ┣ 📄 script.js     ← Core logic of the application
```

---

## 🧠 Core Logic Highlights

- **Locale & Currency Formatting:**  
  Uses `Intl.NumberFormat` and `Intl.DateTimeFormat` to localize balance, summaries, and dates.

- **Transaction Management:**  
  `displayMovements` dynamically renders deposit/withdrawal rows with correct dates.

- **Stateful Session Control:**  
  Auto-logout feature is implemented using `setInterval` with a 10-minute timer.

- **Responsive UI Update:**  
  Functions like `updateUI`, `calcDisplayBalance`, and `calDisplaySummary` ensure that each transaction updates the DOM in real time.

---

## 👤 Demo User Accounts

```
Username: jd     | PIN: 1111  // John Doe
Username: js     | PIN: 2222  // Justine Smith
Username: sa     | PIN: 3333  // Shubh Agrawal
```

---

## 📌 Note

This project is **frontend-only**. It does **not include real authentication** or backend database connections.

---
