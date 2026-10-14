# 🚀 Rafiullah Ibrahimi — Personal Portfolio & Database Engineering Showcase

[![PHP Version](https://img.shields.io/badge/PHP-8.2%2B-777BB4?style=flat&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0%2B-4479A1?style=flat&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A premium, conversion-optimized personal portfolio and technical showcase for **Rafiullah Ibrahimi**, positioning expertise as a **Full-Stack Web Developer, PHP Specialist, and Database Engineer**. 

Designed with a tech-company visual identity, this project demonstrates real full-stack web application development, interactive SQL/ER-diagram engineering tools, responsive client-side routing, and a secure PHP/MySQL backend contact form engine.

---

## 🌟 Key Features & Functional Modules

### 🎨 Design & User Experience
* **Tech-First Dark/Light Theme**: Built with custom CSS custom properties (variables) with a persistent system/manual toggle.
* **Fully Responsive**: Fluid grid system built with Bootstrap 5.3, custom utility classes, and optimized touch targets for mobile, tablet, and desktop.
* **Interactive Terminal & ER Visualizer**: Live code/SQL terminal simulation demonstrating database queries, schema relationships, and normalization steps.

### 💼 Portfolio & Case Studies
* **Filterable Project Gallery**: Dynamic categorization across Full-Stack, Database Systems, Web Apps, and Academic Research.
* **Comprehensive Case Study Modals**: In-depth breakdowns covering problem statements, technical architecture, database design, and key learnings.
* **Verified Credentials Showcase**: Highlights Information Systems B.Sc. degree (3.50/4.00 CGPA), Win Soft Technologies experience, GRE scores (168 Quant / 164 Verbal), and CCNA certifications without fabricated claims.

### 🛠️ Interactive Engineering Tools
* **Interactive SQL Playground**: Switchable schema viewer displaying standard SQL DDL/DML, indexed queries, inner/outer joins, and relational constraint definitions.
* **Interactive Architecture Visualizer**: Step-by-step graphical breakdown of relational schema structures (Tables, PK/FK relationships, and Cardinality).

### 🔒 Security & Backend Infrastructure
* **Secure Contact Form**:
  * Client-side verification and real-time form validation.
  * Server-side processing script using **PHP PDO** with prepared statements to prevent SQL Injection.
  * Native output escaping (`htmlspecialchars`) to mitigate Cross-Site Scripting (XSS).
  * CSRF token verification and basic rate-limiting guards.
  * Fallback to structured client-side handling if running in a static HTML environment.

---

## 🛠️ Technology Stack

| Layer | Technology / Tools |
| :--- | :--- |
| **Frontend UI/UX** | HTML5, CSS3 (Modern Flexbox/Grid, Glassmorphism), JavaScript (ES6+), Bootstrap 5.3 |
| **Typography & Icons** | Inter & Space Grotesk Google Fonts, Font Awesome 6.5 |
| **Backend Processing** | PHP 8.2+ (Modular procedural/OO architecture) |
| **Database System** | MySQL 8.0+ / MariaDB (Prepared statements with PHP PDO) |
| **Local Environment** | XAMPP / WAMP / MAMP / Docker (PHP + MySQL stack) |
| **Version Control** | Git & GitHub |

---

## 📂 Repository Structure

```text
/
├── index.html               # Main single-page application entry point
├── schema.sql               # MySQL database schema & sample data script
├── contact.php              # Secure PHP backend endpoint for form processing
├── assets/
│   ├── css/
│   │   └── style.css        # Custom styles, dark/light themes, custom variables
│   ├── js/
│   │   └── main.js          # Interactive UI controllers, SQL tab engine, theme switcher
│   └── docs/
│       └── cv.pdf           # Downloadable curriculum vitae placeholder
├── LICENSE                  # MIT License file
└── README.md                # Project documentation
