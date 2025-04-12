# 🏅 Membership Club Management System

A role-based Python CLI application designed to manage a sports or hobby club. It supports the registration, scheduling, payments, messaging, and financial tracking for **Members**, **Coaches**, and **Treasurers**.

---

## 💡 Features

### 🔐 Authentication & Registration
- Secure user login and registration for:
  - Members
  - Coaches
  - Treasurers
- Validates input fields and handles duplicate usernames or password mismatches

### 📆 Practice Scheduling
- Coaches can schedule practice sessions
- Notifications are sent to relevant parties automatically

### 💰 Payment Management
- Members can make payments
- Treasurers can:
  - Send payment reminders
  - Pay coach fees
  - Track hall rent
  - View income statements and unpaid dues
- Auto-discount feature for members with 3 consecutive payments

### 💬 Messaging System
- Role-based in-app messaging (e.g., coach to member, treasurer to coach)
- Message center to read received communications

### 📊 Admin Dashboard (CLI)
- Generate income statements
- View unpaid expenses
- Role-based control access (Treasurer-only features)

---

## 🔧 Technologies Used

- **Python 3**
- `termcolor` for colored terminal outputs
- `input()`-based CLI for user interaction
- Data stored in memory via dictionaries

---

## 🚀 How to Run

### 🖥️ Prerequisites
- Python 3 installed
- Install `termcolor` via pip:
```bash
pip install termcolor
