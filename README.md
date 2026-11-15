<div align="center">

<!-- ANIMASI JUDUL PERUSAHAAN -->
<a href="https://github.com/syfrzkngl/Zetoro-Janaloka-Technology-personal">
  <img src="https://readme-typing-svg.demolab.com?font=Plus+Jakarta+Sans&weight=700&size=34&duration=3200&pause=1200&color=22C55E&center=true&vCenter=true&width=680&height=70&lines=Zetoro+Janaloka+Teknologi;Technology+%E2%80%A2+Multimedia+%E2%80%A2+Consulting" alt="Zetoro Janaloka Teknologi" />
</a>

## Company Profile & Official Landing Page

> *"Official digital profile and company website for **CV. Zetoro Janaloka Teknologi** — established in 2021, providing technology solutions, multimedia services, and business consulting."*

<br/>

<!-- TOMBOL LIVE DEMO & BADGES INFO -->
<p align="center">
  <a href="LINK_LIVE_DEMO_KAMU">
    <img src="https://img.shields.io/badge/🌐_Live_Demo-22C55E?style=for-the-badge" alt="Live Demo" />
  </a>
  &nbsp;
  <img src="https://img.shields.io/badge/Established-2021-16A34A?style=for-the-badge" alt="Established 2021" />
  &nbsp;
  <img src="https://img.shields.io/badge/Location-Surabaya%2C_Indonesia-4ADE80?style=for-the-badge" alt="Location Surabaya" />
</p>

<br/>

<!-- TECH STACK (LOGO SAJA) -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,php,mysql,bootstrap,html,css,js,git,github" alt="Tech Stack Logos" />
</p>

</div>

---

### ✨ Key Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📱 Responsive & Interactive UI</h4>
      <ul>
        <li>Built with <b>Bootstrap v5.3.2</b> for seamless mobile & desktop views</li>
        <li>Scroll-based animations powered by <b>AOS (Animate On Scroll)</b></li>
        <li>Dynamic navigation bar with active state highlighting</li>
        <li>Styled with <b>Font Awesome</b> & <b>Bootstrap Icons</b></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>📩 Integrated Contact Management</h4>
      <ul>
        <li>Interactive contact form connected to MySQL (<code>kontak</code> table)</li>
        <li>Instant inquiry forwarding option directly via <b>WhatsApp</b></li>
        <li>Clean submission alerts powered by <b>SweetAlert2</b></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🖼️ Portfolio & Client Showcase</h4>
      <ul>
        <li>Dynamic slider highlighting company partners & clients</li>
        <li>Structured showcase of completed technology & multimedia projects</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h4>📍 Integrated Office Location</h4>
      <ul>
        <li>Embedded <b>Google Maps</b> for direct navigation</li>
        <li>Displays physical office location at <b>Maspion Square, Surabaya</b></li>
      </ul>
    </td>
  </tr>
</table>

---

### 🚀 Installation & Project Guide

<!-- TOMBOL KLIK BUKA-TUTUP -->
<details>
  <summary><b>📄 How to Run and Cloning</b></summary>
  <br/>

  <blockquote>
    <h4>📋 Local Setup Guide (Laragon / XAMPP)</h4>
    <p><i>Make sure <b>PHP</b>, <b>Composer</b>, and <b>MySQL</b> are installed on your computer.</i></p>

    1. Clone Repository
    git clone https://github.com/syfrzkngl/Zetoro-Janaloka-Technology-personal.git
    cd Zetoro-Janaloka-Technology-individual

    2. Install Dependencies
    composer install

    3. Configure .env File
    cp .env.example .env

    Configure your MySQL database connection inside the .env file:
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=your_database_name
    DB_USERNAME=root
    DB_PASSWORD=

    4. Generate Key & Run Migrations
    php artisan key:generate
    php artisan migrate

    5. Start Local Server
    php artisan serve
    (Open http://127.0.0.1:8000 in your browser)

    --------------------------------------------------

    📂 Main Frontend Structure:
    resources/
    └── views/
        └── beranda.blade.php      # Main company homepage

    public/
    ├── css/
    │   └── beranda.css            # Custom stylesheet
    └── img/                       # Company logo, owner photo, client & portfolio images
  </blockquote>

</details>

---

### 🏢 About Zetoro Janaloka Teknologi

**CV. Zetoro Janaloka Teknologi** is a technology-focused company established in 2021, providing technology solutions, multimedia services, and business consulting. This website serves as the company's official digital profile showcasing its services, portfolio, clients, and contact channels.

---

### 📄 License

© 2025 Zetoro Janaloka Teknologi. All rights reserved.
