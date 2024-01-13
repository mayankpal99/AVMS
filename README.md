# Apartment Visitor Management System (AVMS)

## Overview

The Apartment Visitor Management System (AVMS) is a web-based application developed using PHP and MySQL for managing visitors in an apartment complex. This system helps streamline the visitor check-in and check-out process, providing a convenient and efficient solution for apartment residents and management.

## Features

1. **User Authentication:**
   - Secure login for both residents and administrators.
   - Residents can manage their own visitor records.

2. **Visitor Registration:**
   - Residents can register their visitors by providing necessary details such as name, contact information, and the purpose of the visit.

3. **Check-In/Check-Out:**
   - Seamless process for visitors to check in and check out.
   - Timestamps are recorded to maintain an accurate log of visitor movements.

4. **Visitor History:**
   - Residents and administrators can view the visitation history, including check-in and check-out times.

5. **Admin Dashboard:**
   - Administrators have access to a dashboard for monitoring visitor activity and managing system settings.

6. **Search and Filter:**
   - Users can search for specific visitors and filter the visitor log based on various criteria.

7. **Notifications:**
   - Automated notifications for residents upon visitor check-in or check-out.

8. **Security:**
   - Password hashing and secure session management to ensure the confidentiality of user information.
   - Access control measures to restrict unauthorized access to sensitive data.

## Installation

1. **Requirements:**
   - PHP 7.0 or higher
   - MySQL database
   - Web server (e.g., Apache, Nginx)

2. **Setup Database:**
   - Import the provided SQL script (`avms.sql`) into your MySQL database.

3. **Configuration:**
   - Update the database connection parameters in `config.php` with your MySQL credentials.

4. **Web Server Configuration:**
   - Configure your web server to point to the project directory.

5. **Access:**
   - Open your web browser and navigate to the configured URL to access the AVMS.

## Usage

1. **Resident Login:**
   - Residents can log in using their credentials to access the visitor management system.

2. **Visitor Registration:**
   - Residents can register their visitors by filling out the necessary information.

3. **Check-In/Check-Out:**
   - Visitors can check in and check out using the resident's credentials.

4. **View History:**
   - Residents and administrators can view the visitation history on the dashboard.

5. **Admin Features:**
   - Administrators have additional features for managing users, viewing system logs, and modifying system settings.

## Support and Issues

If you encounter any issues or have questions, please feel free to [open an issue](https://github.com/yourusername/avms/issues) on our GitHub repository.

## License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using the Apartment Visitor Management System! If you have any feedback or suggestions, we'd love to hear from you.
