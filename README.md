

<p align="center">
  <img src="https://img.shields.io/badge/PRO--QR-Engineering%20Studio-0f172a?style=for-the-badge&logo=qrcode&logoColor=white" />
  <img src="https://img.shields.io/badge/version-v2.6-2563eb?style=for-the-badge" />
  <img src="https://img.shields.io/badge/status-production%20ready-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/UI-TailwindCSS-38bdf8?style=for-the-badge&logo=tailwindcss" />
  <img src="https://img.shields.io/badge/backend-Firebase-orange?style=for-the-badge&logo=firebase" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/USERNAME/REPO_NAME?style=for-the-badge" />
  <img src="https://img.shields.io/github/forks/USERNAME/REPO_NAME?style=for-the-badge" />
  <img src="https://img.shields.io/github/issues/USERNAME/REPO_NAME?style=for-the-badge" />
  <img src="https://img.shields.io/github/last-commit/USERNAME/REPO_NAME?style=for-the-badge" />
  <img src="https://komarev.com/ghpvc/?username=USERNAME&repo=REPO_NAME&label=Project%20Views&color=2563eb&style=for-the-badge" />
</p>

---

# 🚀 PRO QR – Engineering Studio

**PRO QR** is a professional-grade **QR Code Engineering Studio** designed for developers, designers, and businesses. It enables advanced QR generation, branding, exporting, and cloud-based management with a modern engineering-focused UI.

---

## ✨ Features

### 🔧 QR Generation

* URL QR Codes
* Text QR Codes
* WiFi QR Codes (WPA / WEP / Open)
* vCard QR Codes (Contact Information)

### 🎨 Customization

* Foreground & background color control
* Logo embedding with high error correction
* Live preview with scanner animation
* Professional export-ready design

### 📦 Export & Utility

* Download QR as **PNG**
* Copy encoded QR data
* One-click reset for branding & colors

### 📚 Project Library (Firebase)

* Anonymous authentication
* Automatic QR save history
* View & delete previously generated QR data
* Real-time Firestore sync

### 🧠 UX & Design

* Tailwind CSS modern UI
* Responsive layout (Desktop & Mobile)
* Toast notifications
* Engineering-grade preview panel

---

## 🛠 Tech Stack

| Technology           | Purpose               |
| -------------------- | --------------------- |
| HTML5                | Application structure |
| Tailwind CSS         | UI & styling          |
| JavaScript (ES6)     | Logic & interaction   |
| QRCode.js            | QR generation engine  |
| Firebase Auth        | Anonymous login       |
| Firestore            | QR history storage    |
| Google Fonts (Inter) | Typography            |

---

## 📂 Project Structure

```
pro-qr/
│
├── index.html        # Complete application (UI + logic)
├── README.md         # Documentation
```

> This project is intentionally built as a **single-file professional app** for portability and easy deployment.

---

## 🔥 Firebase Setup (Optional)

To enable **Project Library & History**, configure Firebase:

1. Create a Firebase project
2. Enable **Anonymous Authentication**
3. Enable **Firestore Database**
4. Add your Firebase config inside `index.html`

```js
const localConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "XXXXXX",
  appId: "YOUR_APP_ID"
};
```

> Without Firebase, the app works fully except history storage.

---

## ▶️ How to Run

### Local

```
Open index.html in any modern browser
```

### VS Code (Recommended)

```
Use Live Server extension
```

---

## 🧪 Supported Browsers

* Chrome
* Edge
* Firefox
* Safari

---

## 📌 Version

**v2.6**

---

## 👨‍💻 Author

**Md. Emon Hossain**
CSE Student | Web & Software Developer

---

## 📜 License

This project is open for **learning and personal use**.
For commercial or SaaS usage, please provide proper credit.

---

## 🌟 Future Roadmap

* SVG QR export
* Dark / Light mode toggle
* QR size & margin controls
* Progressive Web App (PWA)
* User dashboard
* QR scan analytics
* AI QR design presets
* Chrome Extension

---

> ⭐ If you like this project, don’t forget to **star the repository** and share it!

