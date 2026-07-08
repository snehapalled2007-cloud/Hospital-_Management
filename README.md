A Hospital Management System API is a good CRUD project. A simple structure is:                              
Hospital-Management-System/
│
├── backend/
│   ├── index.js
│   ├── data.db
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   └── App.css
│   └── package.json
│
├── Hospital-Management-API.postman_collection.json
└── Hospital-Management.postman_environment.json

Features
Dashboard
Add Patient
View Patients
Update Patient
Delete Patient
Search Patient

Add Doctor
View Doctors
Update Doctor
Delete Doctor

Appointment Management
Statistics
SQLite Tables

Patients
Column	Type
id	INTEGER PRIMARY KEY
name	TEXT
age	INTEGER
gender	TEXT
disease	TEXT
doctor	TEXT
phone	TEXT
address	TEXT

Doctors
Column	Type
id	INTEGER PRIMARY KEY
name	TEXT
specialization	TEXT
experience	INTEGER
phone	TEXT
Appointments

Column	Type
id	INTEGER PRIMARY KEY
patientName	TEXT
doctorName	TEXT
date	TEXT
time	TEXT
status	TEXT
REST API Endpoints

Patients
GET /patients
GET /patients/:id
POST /patients
PUT /patients/:id
DELETE /patients/:id
Doctors
GET /doctors
GET /doctors/:id
POST /doctors
PUT /doctors/:id
DELETE /doctors/:id
Appointments
GET /appointments
GET /appointments/:id
POST /appointments
PUT /appointments/:id
DELETE /appointments/:id
Dashboard
GET /dashboard

Example response:

{
  "patients": 25,
  "doctors": 8,
  "appointments": 14
}
Technology Stack

Backend

Node.js
Express.js
SQLite (better-sqlite3)
CORS

Frontend

React (Vite)
CSS
Fetch API
Frontend Pages
Dashboard
Patients
Doctors
Appointments
Statistics

Each page supports:

Add
Edit
Delete
Search
Refresh
Postman Collection

Include requests for:

Patient CRUD
Doctor CRUD
Appointment CRUD
Dashboard API

This makes a complete beginner-friendly full-stack Hospital Management System using Express + SQLite + React (Vite).
