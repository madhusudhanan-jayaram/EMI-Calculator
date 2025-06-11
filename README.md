# 💰 EMI Calculator

An intuitive and easy-to-use **EMI (Equated Monthly Installment) Calculator** that helps users estimate monthly loan payments based on principal amount, interest rate, and tenure.

## 🚀 Features

- Calculate EMI for personal, home, auto, or education loans
- Dynamic input for principal, interest rate, and tenure
- Displays monthly EMI, total interest payable, and total repayment amount
- Clean and responsive UI (if frontend-based)
- Works offline (optional for PWA/mobile)
- Supports different loan types (optional)

## 📸 Demo

![EMI Calculator Demo](demo/demo.gif)  
_(Insert a screenshot or screen recording if available)_

## 🧑‍💻 Tech Stack

| Layer     | Tech Used                |
|-----------|--------------------------|
| Frontend  | HTML, CSS, JavaScript / Angular / React (based on your app) |
| Backend   | Node.js / Spring Boot (optional) |
| Hosting   | GitHub Pages / Netlify / Vercel / Heroku |

## 🧮 Formula Used

EMI = `[P × R × (1 + R)^N] / [(1 + R)^N – 1]`

Where:
- `P` = Principal loan amount  
- `R` = Monthly interest rate (annual interest rate / 12 / 100)  
- `N` = Loan tenure in months

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/emi-calculator.git
cd emi-calculator
