<div align="center">

# 🔐 RTL Login Page

### A modern, animated, RTL-ready login form with a Persian (Jalali / Shamsi) date picker — built with pure HTML, CSS & JavaScript.

<p>
  <img src="https://img.shields.io/github/license/morpheusadam/loginpage?style=for-the-badge&color=4c1" alt="License" />
  <img src="https://img.shields.io/github/stars/morpheusadam/loginpage?style=for-the-badge&color=ffca28" alt="Stars" />
  <img src="https://img.shields.io/github/forks/morpheusadam/loginpage?style=for-the-badge&color=42a5f5" alt="Forks" />
  <img src="https://img.shields.io/github/last-commit/morpheusadam/loginpage?style=for-the-badge&color=8e44ad" alt="Last commit" />
  <img src="https://img.shields.io/github/repo-size/morpheusadam/loginpage?style=for-the-badge&color=e67e22" alt="Repo size" />
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/RTL-Ready-6c5ce7?style=for-the-badge" alt="RTL Ready" />
</p>

</div>

---

## 📖 Overview

**RTL Login Page** is a clean, ready-to-use **login form template** designed for **right-to-left (RTL)** interfaces such as Persian and Arabic apps. It features a dark, glassmorphism-style card on an animated particle background, and integrates a **Jalali (Shamsi) date picker** for Persian calendars.

The page is built with **plain HTML, CSS, and vanilla JavaScript** — no framework or build step required. It includes a center/branch selector, a numeric code field, a password field, a date field with a Persian calendar, and a "remember me" option, with accessibility (ARIA) attributes throughout. The selected center is persisted in `localStorage`, and a built-in Gregorian-to-Jalali conversion fallback ensures the date picker always shows today's Persian date.

It is ideal for **front-end developers** who need a polished, RTL-first sign-in screen they can drop into any project.

> 🔎 **Keywords:** rtl login page, persian login form, jalali datepicker, shamsi date picker, html css login, vanilla javascript login, glassmorphism login, particles.js background, responsive login template.

---

## ✨ Features

- 🌐 **RTL & Persian-ready** — `dir="rtl"` layout with Vazirmatn and Yekan fonts.
- 📅 **Jalali (Shamsi) date picker** — Persian calendar input via `@majidh1/jalalidatepicker`.
- 🔁 **Date fallback** — built-in Gregorian → Jalali conversion so today's date always resolves.
- ✨ **Animated background** — interactive particles powered by `particles.js`.
- 🏢 **Center selector** — choose a branch/center, remembered across visits via `localStorage`.
- 🔑 **Secure inputs** — numeric code, password, and remember-me fields with proper `autocomplete`.
- ♿ **Accessible** — ARIA labels and semantic landmarks for screen readers.
- 🎨 **Glassmorphism UI** — modern dark theme with accent gradients and FontAwesome icons.
- 🪶 **Zero build** — pure HTML/CSS/JS; just open `index.html`.

---

## 🛠️ Tech Stack

| Layer | Technology |
| --- | --- |
| Markup | HTML5 (RTL) |
| Styling | CSS3 (custom properties, glassmorphism) |
| Logic | Vanilla JavaScript |
| Fonts | Vazirmatn, Yekan |
| Date picker | `@majidh1/jalalidatepicker` |
| Background | particles.js |
| Icons | Font Awesome 6 |

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser. No build tools or dependencies to install.

### Installation

```bash
git clone https://github.com/morpheusadam/loginpage.git
cd loginpage
```

### Usage

Simply open `index.html` in your browser, or serve the folder with any static server:

```bash
# Optional: serve locally
npx serve .
# or
python -m http.server
```

The third-party libraries (particles.js, Jalali date picker, fonts) are loaded from CDNs, so an internet connection is required for the full experience.

---

## 🗂️ Project Structure

```text
loginpage/
├── index.html
└── assets/
    ├── css/
    │   ├── styles.css
    │   └── jalalidatepicker.css
    ├── js/
    │   ├── app.js
    │   └── jalalidatepicker.js
    └── img/
        └── tabiat-logo.svg
```

---

## 🤝 Contributing

Contributions are welcome! Open an [issue](https://github.com/morpheusadam/loginpage/issues) or submit a pull request with improvements, new themes, or accessibility enhancements.

## 📜 License

Free to use and modify. See [`LICENSE`](LICENSE) if present, otherwise released under the MIT License.

---

<div align="center">

### 👤 Author — Morpheus Adam

Web developer & cheerful hacker · PHP · Laravel · Go

<p>
  <a href="https://github.com/morpheusadam"><img src="https://img.shields.io/badge/GitHub-morpheusadam-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://sam.zeonic.me"><img src="https://img.shields.io/badge/Website-sam.zeonic.me-4c1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:morpheusadam95@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

⭐ **If you like this template, consider giving it a star!** ⭐

</div>


---

## ⭐ Star History

<a href="https://star-history.com/#morpheusadam/loginpage&Date">
  <img src="https://api.star-history.com/svg?repos=morpheusadam/loginpage&type=Date" alt="loginpage — Star History Chart" width="70%" />
</a>

<div align="center">

### If this project helps you, please give it a ⭐

A star helps other developers discover **loginpage** and supports continued development.

</div>
