# BankistApp

BankistApp is a modern banking application divided into two parts: **Landing Page** and **Banking App**. This project is built as part of a JavaScript course, with future plans to connect it to a real backend.

---

## 📚 Project Structure

- `landingPart/` – Contains the **landing page** with a modern design and multiple interactive features.  
- `app/` – Contains the **banking application** where users can log in and manage their accounts.

---

## ✨ Features

### 🔸 Landing Page (`landingPart/`)
- **Modal windows** – Interactive modals open and close with animations.
- **Smooth scrolling** – Clickable links and buttons smoothly scroll to page sections.
- **Tabbed component** – Tabs that switch between different content sections.
- **Menu fade animation** – When hovering over the navigation menu, other links and the logo fade out for better focus.
- **Sticky navigation** – The navbar sticks to the top when scrolling past the header.
- **Section reveal on scroll** – Sections are revealed with animations as the user scrolls.
- **Lazy loading of images** – Images load dynamically as they approach the viewport, improving performance.
- **Slider (carousel)** – A dynamic image slider with dots navigation and keyboard controls.
- **Responsive design** – The landing page adapts to various screen sizes for a seamless user experience.
- **"Create account" option** – Front-end-only form for creating an account (not yet functional).

---

### 🔸 Banking App (`app/`)
- User login with predefined accounts:
  - `js` (PIN: `1111`)
  - `sd` (PIN: `2222`)
  - `mv` (PIN: `3333`)
  - `sg` (PIN: `4444`)
- View all transactions (deposits and withdrawals).
- Transfer money to another user by entering their username.
- Request a loan (only if the user has at least one deposit of 10% or more of the requested amount).
- Close (delete) an account.
- Dynamic calculation of account balance, total deposits, withdrawals, and interest.
- Transaction sorting functionality.
- Currently front-end only – all accounts are hardcoded in the app.

---

## 🚀 Future Plans
- Connect the landing page and banking app to a real backend with database and authentication.
- Enable actual account creation and user authentication.
- Further improve the design and optimize UX/UI.

---

💡 This app is currently **front-end only**, but it’s a solid foundation for connecting to a real backend in the future.

---
