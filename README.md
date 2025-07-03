# 🏦 Monthly Bank Statement Generator – OpenText Exstream Project

This project is a complete simulation of a **Monthly Bank Statement** generation system developed using **OpenText Exstream**.  
It showcases real-world dynamic document generation with scripting, table overflow, conditional logic, and batch execution support.

---

## 📌 Features

- 🔄 Dynamic multi-page transaction table with overflow
- 🧮 Scripting logic to calculate running balance
- ⚠️ Conditional alert for low balance based on threshold
- 📥 XML-based data input (customer + transactions)
- 📤 Control file for batch processing (`control.ctl`)
- 📑 Professional layout with header, summary, and footer
- 🧠 Designed using **OpenText Exstream Designer 16** and **Design Manager**
- 🧾 Empower-ready structure (optional)

---

## 📁 Project Structure

```plaintext
BankStatement_Project/
├── input.xml          # Customer & transaction data
├── script used in formula variable to handle the remaining balance and interest           # Balance calculation logic
├── control.ctl        # Batch config
├── layout.png         # Layout image/mockup
├── output.pdf         # Sample generated statement
├── README.md          # Project documentation (this file)
