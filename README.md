<div align="center">

  <h1>🇧🇩 Donate Bangladesh</h1>

  <p>
    An interactive, transparent community donation and disaster relief web platform built to facilitate emergency aid and support causes across Bangladesh.
  </p>

  <p>
    <a href="https://saudabintinoor.github.io/Donate-Bangladesh/" target="_blank">
      <img src="https://img.shields.io/badge/Live_Demo-Visit_Site-2ea44f?style=for-the-badge&logo=githubpages&logoColor=white" alt="Live Demo" />
    </a>
    &nbsp;
    <a href="https://github.com/saudabintinoor/Donate-Bangladesh">
      <img src="https://img.shields.io/badge/Source_Code-Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" />
    </a>
  </p>

</div>

---

## 📌 Overview

**Donate Bangladesh** is a client-side humanitarian aid application designed to streamline contributions for critical emergency relief efforts, such as flood response in Feni, Noakhali, and community support funds. 

The application provides real-time client-side calculation, live donation logging, balance validation, and seamless tab transitions between active campaigns and dynamic transaction history.

---

## ✨ Key Features

- **Dynamic Campaign Cards:** Multi-cause donation sections with targeted fund allocation (e.g., Flood Relief in Feni, Quota Movement Aid).
- **Interactive Balance Management:** Real-time balance deductions from the account balance paired with instantaneous campaign total updates.
- **Input Validation & Modals:** Prevents invalid, non-numeric, or negative inputs with clear visual alert feedback and confirmation popups upon successful donation.
- **Live Transaction History:** Automatically appends an authenticated time-stamped transaction log for each donation.
- **Tab Navigation & Blog Section:** Dynamic view toggling between live donation campaigns, historical logs, and an informative FAQ/blog page (`blog.html`).
- **Fully Responsive UI:** Styled with Tailwind CSS to ensure accessibility and layout consistency across all screen sizes.

---

## 🛠️ Built With

- **HTML5:** Semantic page layouts, accessible forms, and document structure.
- **Tailwind CSS (`tailwind.config.js`):** Utility-first styling framework for modular responsive design.
- **JavaScript (Vanilla ES6+):** Core application business logic, DOM manipulation, input validations, and state tracking split across modular scripts:
  - `donation.js` & `feniDonation.js` – Campaign calculation and account balance deductions.
  - `features.js` – Dynamic tab toggling, history rendering, and modal interactions.
  - `quota.js` – Specific fund workflows.
- **GitHub Pages:** Static deployment and hosting.

---

## 🚀 Getting Started (Local Setup)

To run this project locally on your machine:

### 1. Clone the repository
```bash
git clone [https://github.com/saudabintinoor/Donate-Bangladesh.git](https://github.com/saudabintinoor/Donate-Bangladesh.git)
