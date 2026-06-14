# 🏛️ ClubConnect — College Club Management Portal

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?style=flat-square&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-Database-4479A1?style=flat-square&logo=mysql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

A web-based club management portal for college students and administrators. Built for **MIT World Peace University (MITWPU)**, ClubConnect allows students to explore clubs, while admins manage memberships, events, and notices.

---

## Features

### Student Portal
- 🔍 Browse all active clubs and their details
- 📝 Register and manage club membership
- 🔔 View club notices and announcements
- 👤 Personal dashboard with enrolled clubs

### Admin Portal
- ➕ Create, edit, and delete clubs
- 👥 Manage student memberships and approvals
- 📢 Post notices and updates to club members
- 📊 Dashboard with overview statistics

---

## Tech Stack

| Technology | Purpose |
|-----------|---------|
| PHP | Backend server-side logic |
| MySQL | Database for clubs, users, notices |
| TailwindCSS | Responsive UI styling |
| HTML5 | Page structure |
| Animate.css | UI animations |

---

## Project Structure

```
clubconnect/
├── admin/             # Admin dashboard and management pages
├── home/              # Homepage content
├── user/              # Student-facing pages
├── ourclubs/          # Club listing and details
├── create_account/    # Registration flow
├── dashboard/         # Post-login dashboard
├── images/            # Assets and logos
├── dbconnect.php      # Database connection
├── index.php          # Entry point (role selection)
├── userlogin.php      # Student login
└── clubconnect.sql    # Database schema
```

---

## Getting Started

### Prerequisites

- PHP 7.4+ / XAMPP / WAMP
- MySQL

### Setup

```bash
# Clone the repository
git clone https://github.com/pranotivarpe/clubconnect.git
```

1. Import `clubconnect.sql` into your MySQL database
2. Update `dbconnect.php` with your database credentials:
   ```php
   $conn = mysqli_connect("localhost", "root", "", "clubconnect");
   ```
3. Start your local server (XAMPP/WAMP) and navigate to `http://localhost/clubconnect`

---

## Screenshots

| Page | Description |
|------|-------------|
| Landing Page | Role selection — Admin or User login |
| User Dashboard | Enrolled clubs and notices |
| Admin Panel | Club management and member approvals |