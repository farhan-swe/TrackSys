
# 🚀 TrackSys - PHP Order Tracking System

[![PHP Version](https://img.shields.io/badge/PHP-8.2+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net/)
[![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/farhan-swe/tracking-system?style=for-the-badge&logo=github)](https://github.com/farhan-swe/tracking-system/commits/main)

A robust and feature-rich **Order Tracking System** built with PHP and MySQL, designed to provide a seamless experience for both administrators and customers. This system allows admins to manage orders efficiently, while customers can easily track their shipment status in real-time.

---

## ✨ Features

-   🎨 **Modern & Professional UI:** A clean, responsive dashboard with a dark/light mode toggle and customizable color schemes.
-   🔐 **Secure Authentication:** A complete login and registration system for admins with secure password hashing.
-   📊 **Admin Dashboard:** A comprehensive dashboard to add, update, and delete orders.
-   🤖 **Automated Customer IDs:** Sequentially generates unique Customer IDs (e.g., KS000001).
-   📦 **Live Order Tracking:** A customer-facing page where users can track their order status with an animated progress bar.
-   📤 **Data Export:** Ability to export all order data as a CSV file.
-   📱 **Responsive Design:** Works perfectly on desktop, tablet, and mobile devices.

---

## 📸 Screenshots (Conceptual)

*   **Admin Dashboard:** A central hub to manage all orders, view statistics, and customize settings.
*   **Customer Tracking Page:** A simple yet elegant interface for customers to check their order status.
*   **Settings Panel:** Change themes, colors, and update admin profile information.

---

## 🛠️ Tech Stack

-   **Backend:** PHP 8.2+
-   **Database:** MySQL 8.0+
-   **Frontend:** HTML5, CSS3, Vanilla JavaScript
-   **Icons:** Font Awesome
-   **Fonts:** Google Fonts (Poppins)

---

## 📁 Project Structure

```
tracking-system/
│
├── admin/                  # Admin Panel Files
│   ├── index.php          # Admin Dashboard Main Page
│   ├── login.php          # Admin Login Page
│   ├── register.php        # Admin Registration Page
│   ├── logout.php         # Admin Logout Script
│   ├── auth_logic.php     # Login/Registration Logic
│   ├── register_logic.php  # Registration Logic
│   ├── settings_view.php  # Settings Page UI
│   ├── orders_view.php    # Orders Management UI
│   ├── customers_view.php # Customers List UI
│   ├── dashboard_view.php# Dashboard Stats UI
│   ├── style.css          # Admin Panel Styles
│   └── script.js          # Admin Panel Scripts
│
├── api/                   # Backend API Endpoints
│   └── track.php          # API for Customer Tracking
│
├── customer/              # Customer-facing Page
│   ├── index.php          # Customer Tracking Page
│   ├── tracking_style.css # Customer Page Styles
│   └── tracking_script.js# Customer Page Scripts
│
├── config.php             # Database Configuration
├── database.sql           # Database Schema
└── README.md              # This File
```

---

## 🚀 Installation

1.  **Prerequisites:**
    -   XAMPP/WAMP/MAMP (or any similar local server environment).
    -   A web browser (Chrome, Firefox, etc.).

2.  **Clone the Repository:**
    ```bash
    git clone https://github.com/farhan-swe/TrackSys.git
    ```

3.  **Database Setup:**
    -   Start your Apache and MySQL servers from the XAMPP control panel.
    -   Navigate to `http://localhost/phpmyadmin` in your browser.
    -   Create a new database (e.g., `ecommerce_tracking`).
    -   Select the newly created database and click on the "Import" tab.
    -   Choose the `database.sql` file from the project's root directory and click "Go".

4.  **Configuration:**
    -   Open the `config.php` file in the root directory.
    -   Update the database credentials (`DB_SERVER`, `DB_USERNAME`, `DB_PASSWORD`, `DB_NAME`) to match your setup.

5.  **Access the Application:**
    -   **Admin Panel:** `http://localhost/tracking-system/admin/`
    -   **Customer Tracking:** `http://localhost/tracking-system/customer/`

---

## 📖 Usage

### For Admins

1.  **Login:**
    -   Navigate to the admin panel.
    -   The default credentials are `admin` / `password123`.
    -   **IMPORTANT:** For security, it is highly recommended to register a new admin and delete the default one.

2.  **Manage Orders:**
    -   From the dashboard, you can add new orders with custom tracking IDs.
    -   Update the status of existing orders (Processing, Packed, On the Way, etc.).
    -   Delete orders if necessary.

3.  **Customize:**
    -   Go to the "Settings" page to change the theme, color scheme, and update your profile.

### For Customers

1.  **Track Order:**
    -   Go to the customer tracking page.
    -   Enter the tracking ID provided to you (e.g., `KH000001`).
    -   Click the "Track" button to see the current status of your order.

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👨‍💻 Author

Made with ❤️ by **[farhan-swe](https://github.com/farhan-swe)**

---

### 🙏 Acknowledgements

-   [Font Awesome](https://fontawesome.com/) for the amazing icons.
-   [Google Fonts](https://fonts.google.com/) for the 'Poppins' font.
