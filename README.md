# 🏢 Building Management System (BMS) - Frontend

![Homepage Screenshot](./src/assets/readmebanner.png)

---

## 📌 Project Overview

The **Building Management System (BMS)** is a modern web application designed to simplify the management of a building. It provides a smooth and user-friendly experience for both **users** and **admins**, with a focus on responsive design, clean UI, and efficient functionality.

---

## 🌐 Live Site

🔗 https://Buildexia.netlify.app

---

## 🔐 Admin Access (For Testing)

Use the following credentials to access admin features:

* **Email:** [turjo@admin.com](mailto:turjo@admin.com)
* **Password:** Turjo123

---

## 🚀 Key Features

1. **Responsive Design**
   Works perfectly on mobile, tablet, and desktop.

2. **Dynamic Navbar**
   Shows user profile image and changes options based on login state.

3. **Interactive Banner**
   Auto-sliding images for better UI experience.

4. **About Section**
   Clean and informative building details.

5. **Coupons Section**
   Displays available offers attractively.

6. **Location Section**
   Shows apartment location (can include map).

7. **Authentication System**

   * Login & Registration
   * Google & GitHub login

8. **Apartment Listing**

   * Room browsing
   * Filtering & pagination
   * Agreement system

9. **Notifications**
   Uses Toasts/Sweet Alerts for:

   * Login success
   * CRUD operations
   * Registration feedback

10. **Secure Configuration**
    Uses environment variables for Firebase & API keys.

---

## 🛠️ Technology Stack

* **Frontend Framework:** React.js
* **State Management:** Context API
* **Data Fetching:** TanStack Query
* **Styling:** Tailwind CSS
* **UI Library:** DaisyUI
* **Notifications:** React-Toastify / SweetAlert2
* **Authentication:** Firebase
* **Icons:** React Icons

---

## 🔑 Environment Variables

Create a `.env` file inside the project root and add:

```env
REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id

REACT_APP_API_URL=http://localhost:5000
```

---

## ⚙️ Installation & Setup Guide

Follow these steps carefully:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/tareqahmed2/Buildexia-client-side
```

---

### 2️⃣ Navigate to Project Folder

```bash
cd Buildexia-client-side
```

---

### 3️⃣ Install Dependencies

```bash
npm install
```

---

## ⚠️ Important (Node Version Issue)

You are currently using:

```bash
node v25.9.0
```

👉 This version is **too new** and may cause dependency conflicts.

### ✔️ Solution:

Run:

```bash
npm install --force
```

👉 This will ignore dependency conflicts and install everything.

---

### 💡 Recommended Node Version

For best stability, use:

* Node.js **18.x** or **20.x (LTS)**

---

## ▶️ Run the Project

```bash
npm run dev
```

or (depending on setup):

```bash
npm start
```

---

## 📂 Project Structure (Basic)

```
src/
 ├── assets/
 ├── components/
 ├── pages/
 ├── hooks/
 ├── context/
 └── utils/
```

---

## 🧠 Notes & Tips

* Always create `.env` file before running
* Never share your API keys publicly
* Use correct Node version to avoid errors
* If install fails → use `--force`

---

## 👥 Team Collaboration Tip

Since you are working with multiple members on one laptop:

* Always set Git identity before commit:

  ```bash
  git config user.name "Your Name"
  git config user.email "your@email.com"
  ```
* Use clear commit messages:

  ```bash
  git commit -m "Tareq: added login feature"
  ```

---

## 🎯 Final Status

✔️ Fully responsive
✔️ Authentication system ready
✔️ Admin dashboard working
✔️ Production-ready frontend

---

If you want, I can also:

* Fix your README design (more professional)
* Add backend README
* Or prepare this for submission (SWE project)

Just tell me 👍
