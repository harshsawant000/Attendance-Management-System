# Attendance-Management-System


A simple web-based attendance management system built using PHP, MySQL, JavaScript, HTML, and CSS. It provides a structured interface for teachers and students to interact with attendance data securely and efficiently.

## 🌟 Features

- **User Login System**  
  - Secure login for students and teachers via `login.php`.

- **Student Attendance Recording**  
  - Teachers can mark attendance per student for each day.
  - Real-time UI updates using AJAX (`ajaxhandler/` directory).

- **Student Dashboard**  
  - Students can check their attendance history and receive status updates.

- **CSV Report Export**  
  - Attendance data can be exported to CSV (`report.csv`).

- **Email Notification (Optional)**  
  - Email integration script in `email.php` (customizable for alerts).

## 🛠 Tech Stack

- **Frontend:** HTML, CSS, JavaScript, AJAX
- **Backend:** PHP
- **Database:** MySQL

## 📁 Project Structure

```
attendanceapp/
├── ajaxhandler/        # Handles AJAX requests for smooth UI updates
├── css/                # Styling files
├── js/                 # JavaScript files for frontend interactivity
├── database/           # Contains database connection/config
├── attendance.php      # Main logic for marking attendance
├── login.php           # Login page
├── email.php           # Optional email sending feature
├── report.csv          # Sample exportable attendance report
```

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/harshsawant000/Attendance-Management-System.git
   ```

2. **Set Up Database**
   - Create a MySQL database.
   - Import the provided SQL file in the `database/` directory (if available).

3. **Configure Connection**
   - Edit `database/connection.php` to add your MySQL credentials.

4. **Deploy Locally**
   - Use a local server (e.g., XAMPP/WAMP) and place the `attendanceapp` folder in the `htdocs`.

5. **Access the System**
   - Navigate to `http://localhost/attendanceapp/login.php` in your browser.

## 📌 Notes

- This project is best suited for small institutions or as a learning project.
- Customize the UI or add roles (admin/teacher/student) as needed.

