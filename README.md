# 💰 BudgetBuddy – Expense Tracking & Budget Management App

**BudgetBuddy** is a responsive, user-friendly full-stack web application built for managing personal budgets and tracking expenses. It provides a seamless experience from authentication to visualizing expenses using interactive dashboards.

---

## 📌 Project Overview

- Custom-built web application for managing budgets and expenses.
- Ensures a seamless user experience with dynamic routing and authentication.
- Offers real-time visualization of spending through intuitive UI elements.

---

## 🔑 Core Features

### 🔐 Authentication
- Secure third-party login via Clerk.
- Session-based redirection to dashboard or budget setup.

### 📁 Budget Management
- Create, edit, and delete custom budgets.
- Set names, emojis, and budget limits.
- All data persists using a cloud-based database.

### 💸 Expense Tracking
- Add, edit, and delete individual expenses.
- Track total, used, and available budget amounts in real time.

### 📊 Visualization
- Bar charts to display budget status (used vs available).
- Summary dashboard with latest budgets and expense stats.

### 🧭 Navigation & Flow
- Auto-redirect based on whether user has existing budgets.
- Budget list and dashboard are both accessible anytime.

### 🔒 Logout
- Secure logout with session clearing and redirection to login page.

---

## 🛠 Tech Stack

| Layer        | Technologies Used             |
|--------------|-------------------------------|
| Frontend     | Next.js, HTML5, CSS3, JavaScript |
| Backend      | Drizzle ORM, Neon Database     |
| Authentication | Clerk                        |
| Charts       | ReactCharts                   |
| UI Libraries | Tailwind CSS       |

---

## 🧾 Use Case Flow

### 1. **User Authentication**
- Click link → Redirect to login → Choose provider → Enter credentials → Redirect to dashboard.

### 2. **Initial Dashboard Navigation**
- If user has no budgets → Redirect to budget creation.
- Else → Load dashboard with existing data.

### 3. **Budget Creation**
- Click “Create Budget” → Choose emoji, enter name & amount → Save.

### 4. **Expense Management**
- Select a budget → Add expenses with details → View budget summary.
- Edit/delete expenses and budgets as needed.

### 5. **Visualization & Logout**
- View all budgets in dashboard via bar charts.
- Logout safely with session termination.

---

## 📁 Folder Highlights

- `pages/` – Routes like home, dashboard, budgets.
- `components/` – UI components (forms, cards, charts).
- `lib/` – Drizzle ORM configuration & database queries.
- `public/` – Static files (images, icons).
- `styles/` – Custom styling files.

---

## 📌 Screenshots (optional)

Add screenshots here when available for:
- Login Page
- Dashboard
- Budget Creation
- Expense Form
- Charts View

---

## 🙌 Credits

Crafted with care by Vishwa Panchal  
**GitHub:** [@vishwapanchal](https://github.com/vishwapanchal)
