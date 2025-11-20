# Document Management & Lab Access System (UMNG)

[![Leer en Español](https://img.shields.io/badge/Leer_en-Español-red?style=for-the-badge&logo=none)](README.md)

![Project Status](https://img.shields.io/badge/Status-Functional_Prototype-orange)
![Tech Stack](https://img.shields.io/badge/Stack-HTML_CSS_JS_PHP-blue)

> **⚠️ WARNING: Server Status**
> Currently, the backend server (PHP/MySQL) is **disabled**. Therefore, _login_, _registration_, and _data submission_ features are not operational in the live demo. The site can be viewed in "frontend-only" mode to showcase the interface, layout, and form validation.

---

### 🌐 [View Live Website](https://pintomultimedia2002.github.io/Servicio-web/)

---

Web application developed as a final project for the **Internet Technologies (2023-1)** course. This system simulates a web service for student and professor authentication, facilitating laboratory access requests and administrative document review at **Universidad Militar Nueva Granada**.

## 📖 Description

The project addresses the need to digitize the academic document review workflow. It allows users to register and log in based on their role (Administrative or Professor) to perform specific tasks:

- **Professors:** Document submission, signature review, and error tracking.
- **Administrative Staff:** Review document lists, approve requests, and manage hiring processes.

## 🚀 Key Features

### 🔐 Authentication & Security

- **Login & Registration:** Custom UI with access forms.
- **Client-Side Validation:** JavaScript scripts (`login.js`) to validate empty fields and ensure data integrity before submission.
- **Basic Backend:** MySQL database connection via PHP for user registration.

### 👨‍🏫 Professor Module

- **File Upload:** Visual interface simulating "Drag & Drop" for documents.
- **Status Feedback:** Success confirmation screens or error reporting dashboards.

### 🏢 Administrative Module

- **Review Dashboard:** Dedicated views to review documents, signatures, and hiring processes.
- **Workflow:** Functional buttons to "Approve" or mark items "To Correct" in document lists.

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3 (Responsive design and custom positioning), JavaScript (Vanilla).
- **Backend:** PHP (Form handling and DB connection).
- **Database:** MySQL.

## 📂 Project Structure

```text
├── css/                 # Styles for Login and Registration
├── imagenes/            # Graphic resources (Icons, Logos)
├── img/                 # Background images and structure
├── js/                  # Validation logic (login.js)
├── php/                 # Server scripts (data.php)
├── old_site.../         # Dashboard Views (Admin/Professor)
├── index.html           # Login Page
└── registerLogin.html   # Registration Page
```

## ⚙️ Local Installation

To run the full functionality (including PHP):

1. **Clone the repository:**

   ```
   git clone https://github.com/pintomultimedia2002/Servicio-web.git
   ```

2. **Server Setup:**

   - Requires a local server like **XAMPP** or **WAMP** .
   - Move the files to the public folder (`htdocs` or `www`).

3. **Database:**

   - Configure the `user` table in MySQL with columns: `nombre`, `apellido`, `codigo`, `email`, `password`.
   - Update credentials in `php/data.php`.

## ✒️ Authors

- **David Pinto** - [GitHub](https://github.com/pintomultimedia2002)
- **Santiago Henao** - [GitHub](https://github.com/Sant-Hen)

---

_This project was developed for academic purposes for Universidad Militar Nueva Granada._

