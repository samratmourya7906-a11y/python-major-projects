# python-major-projects
# 🎓 Student Management & Result System (GUI-based)

A comprehensive, desktop-based **Student Management and Academic Portal** developed using Python Tkinter, SQLite3, and ReportLab. This application provides a modern user interface for managing student academic records, marksheet PDF generation, attendance tracking, assignments, leave requests, sports activities, and competitive exam details.

---

## 🌟 Key Features

### 🔐 1. Authentication & Security
- **Modern Login Interface:** Sleek login window featuring dynamic background image slideshows.
- **Input Validation:** Error window (404 Error prompt) triggers upon invalid password formats or special character entries.
- **Back to Home / Logout System:** Smooth navigation between the dashboard and the login screen.

### 📚 2. Academic & Student Information
- **Manage Students:** Add, Update, Delete, and Search student records (Roll No, Name, Branch, Semester, Contact, Address, Photo File Path).
- **Interactive Database Grid:** Real-time data visualization using `ttk.Treeview`.

### 📊 3. Result & Marksheet PDF Generator
- **Automatic Grade & Percentage Calculation:** Instantly calculates percentages and assigns grades (A+, A, B, C).
- **PDF Export:** Integrated `ReportLab` engine to download official PDF marksheets with a single click.

### 💳 4. Fees Structure & Tracking
- **Fee Management:** Track total course fees, paid amounts, remaining dues, and payment status (Paid / Pending).

### 📝 5. Examination Form Portal
- **Exam Registrations:** Form submission for semester end examinations and course subjects.

### 📅 6. Attendance Management
- **Attendance Tracker:** Record total classes and present days with automated percentage and attendance status alerts (Good / Short Attendance).

### 📑 7. Assignments & Online Leave Application
- **Assignment Portal:** Submit assignment titles, subjects, and deadline tracking.
- **Online Leave Requests:** Apply for leave online with dates and reason tracking (Pending / Approved status).

### 🏆 8. Sports & Qualifying Competitive Exams
- **Sports & Games Tracking:** Record sports category, game names, and student achievements.
- **Qualifying Exams:** Store records of competitive exam participation (GATE, CAT, NIMCET, etc.), ranks, scores, and years.

---

## 🛠️ Tech Stack & Libraries Used

- **Language:** Python 3.x
- **GUI Framework:** `tkinter`, `ttk`
- **Database:** `sqlite3` (Embedded Relational Database)
- **Image Processing:** `Pillow (PIL)`
- **PDF Generation:** `reportlab`
- **Network Requests:** `urllib` (for downloading slideshow assets)

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed on your system along with the required libraries.

```bash
pip install pillow reportlab
