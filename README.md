# Student Database Management System using Django

## 📌 Project Description
The **Student Database Management System** is a web-based application built using Django. It provides functionalities to manage student records, including creating, updating, viewing, and deleting student details. The system ensures efficient handling of student data with a user-friendly interface.

## 🚀 Features
- 🔹 Add new students to the database
- 🔹 Update student information
- 🔹 View student details
- 🔹 Delete student records
- 🔹 Search and filter student data
- 🔹 Authentication system for secure access

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, Bootstrap
- **Backend:** Django, Python
- **Database:** SQLite (Default), can be switched to MySQL/PostgreSQL
- **Other:** Django ORM, Django Templates

## 📂 Project Structure
```
Student-Database-Management-System/
│-- manage.py
│-- db.sqlite3
│-- README.md
│-- studentdbms/  (Main Django Project Folder)
│   │-- settings.py
│   │-- urls.py
│   │-- wsgi.py
│-- students/  (Django App)
│   │-- models.py
│   │-- views.py
│   │-- urls.py
│   │-- templates/
│   │   │-- home.html
│   │   │-- contact.html
│-- static/  (CSS, JS, Images)
```

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/Student-Database-Management-System-using-Django.git
cd Student-Database-Management-System-using-Django
```

### 2️⃣ Create and Activate a Virtual Environment
```bash
python -m venv venv  # Create Virtual Environment
source venv/bin/activate  # Activate (For macOS/Linux)
venv\Scripts\activate  # Activate (For Windows)
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations
```bash
python manage.py migrate
```

### 5️⃣ Create a Superuser (For Admin Access)
```bash
python manage.py createsuperuser
```

### 6️⃣ Run the Development Server
```bash
python manage.py runserver
```
Access the application at **http://127.0.0.1:8000/**

## 👨‍💻 Usage
1. Admin can add, update, and delete student records.
2. Users can search for student details using filters.
3. Secure login ensures authorized access to the system.

## 🤝 Contributing
Contributions are welcome! If you find any issues or have suggestions, feel free to open an issue or submit a pull request.

## 📬 Contact
For any queries, reach out at [your-email@example.com](mailto:your-email@example.com).

