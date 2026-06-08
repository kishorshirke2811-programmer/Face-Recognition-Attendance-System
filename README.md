# Face Recognition Attendance System

## Overview

The Face Recognition Attendance System is a web-based application developed using Django and OpenCV that automates attendance management through facial recognition technology. The system captures and recognizes student faces in real time, reducing manual attendance efforts and improving accuracy.

## Features

* User Authentication (Login/Logout)
* Student Registration
* Face Dataset Collection
* Face Detection and Recognition
* Automatic Attendance Marking
* Attendance Record Management
* Admin Dashboard
* Secure Database Storage
* Real-Time Face Recognition

## Technology Stack

### Backend

* Python
* Django

### Computer Vision

* OpenCV
* NumPy

### Database

* SQLite

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

## Project Structure

```text
Face-Recognition-Attendance-System/
│
├── attendance/
├── static/
├── templates/
├── media/
├── manage.py
├── db.sqlite3
├── requirements.txt
└── README.md
```

## Installation

### Clone Repository

```bash
git clone https://github.com/kishorshirke2811-programmer/Face-Recognition-Attendance-System.git
cd Face-Recognition-Attendance-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py migrate
```

### Run Server

```bash
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

## Working Flow

1. Register students in the system.
2. Capture face datasets.
3. Train the recognition model.
4. Detect and recognize faces.
5. Automatically mark attendance.
6. Store attendance records in the database.

## Future Enhancements

* Email Notifications
* Attendance Analytics Dashboard
* Cloud Database Integration
* Mobile Application Support
* Multi-Camera Support
* Face Mask Recognition

## Author

**Kishor Shirke**

Final Year Information Technology Student

GitHub: https://github.com/kishorshirke2811-programmer
