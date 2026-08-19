

# 🎓 Student Performance Tracker

A full-stack Flask web application for managing student marks, tracking academic performance, and visualizing student analytics.

## 📌 Overview

Student Performance Tracker is a web-based academic management application built using Python and Flask.

It allows users to add students, manage multiple subjects and marks, calculate grades and averages, analyze performance using charts, search and filter records, generate reports, and export data to CSV.

## ✨ Features

- 👨‍🎓 Student management
- 📚 Multiple subjects per student
- 📝 Marks and automatic grade calculation
- 🧮 Automatic average calculation
- 🏆 Top performer identification
- 📊 Grade distribution visualization
- 📈 Subject performance analytics
- 🔎 Student and subject search
- 🎯 Grade-based filtering
- ✏️ Edit student records
- 🗑️ Delete student records
- 📄 Individual student reports
- 📥 CSV data export
- 🛡️ Input validation
- 💾 SQLite database persistence
- 📱 Responsive mobile-friendly interface

## 🛠️ Technologies Used

### Backend

- Python
- Flask
- SQLite

### Frontend

- HTML5
- CSS3
- JavaScript

### Visualization

- Chart.js

### Template Engine

- Jinja2

### Data Export

- CSV

## 🗂️ Project Structure

```text
student_performance_tracker/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   ├── index.html
│   ├── edit.html
│   └── report.html
│
└── static/
    └── style.css

⚙️ How to Run

1. Clone the Repository

git clone https://github.com/YOUR-USERNAME/student_performance_tracker.git

2. Open the Project Folder

cd student_performance_tracker

3. Install Dependencies

pip install -r requirements.txt

4. Run the Application

python app.py

5. Open in Browser

http://127.0.0.1:5000

📊 Dashboard

The application provides a dashboard containing:

Total students

Average marks

Highest marks

Pass rate

Grade distribution

Subject averages

Top performer

Student records


🗄️ Database

The application uses SQLite for persistent data storage.

Student information, subjects, marks, and grades are stored in the application's database.

The database file is excluded from version control using .gitignore.

🎯 Project Goals

This project was developed to practice and demonstrate:

Python programming

Flask web development

CRUD operations

Database management

Frontend development

JavaScript interaction

Data visualization

Form validation

CSV file export

Responsive UI design


🚀 Future Improvements

Possible future enhancements include:

User authentication

Student login system

Attendance tracking

PDF report generation

Performance comparison

Semester-wise analytics

Cloud database integration

Deployment to a public web server


👨‍💻 Author

Sachin Karthik

B.Tech Student | Data Science


---

⭐ If you find this project useful, consider giving the repository a star.

