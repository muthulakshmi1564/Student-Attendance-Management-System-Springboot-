# Student-Attendance-Management-System-Springboot-
This project is a web-based application developed using Spring Boot that allows students to mark their attendance securely using OTP verification. The system also provides an admin panel to manage students and monitor attendance records.

# 🎓 Student Attendance Management System

A web-based application built using Spring Boot that allows students to mark attendance securely using OTP verification. The system also provides an admin panel to manage students and monitor attendance records.

---

## 🚀 Features

- 🔐 Secure login with encrypted passwords (BCrypt)
- 📧 OTP-based authentication via email
- ⏰ Time-restricted attendance marking
- 👨‍🎓 Student registration and login
- 📊 Student dashboard with attendance history
- 👨‍💼 Admin dashboard to manage students
- 📝 View complete attendance records
- ❌ Prevent duplicate attendance entries

---

## 🛠️ Tech Stack

- **Backend:** Spring Boot
- **Frontend:** Thymeleaf, HTML, CSS
- **Database:** MySQL
- **Security:** Spring Security, BCrypt
- **Email:** JavaMailSender

---

## 🧱 Architecture

This project follows a layered architecture:

- Controller Layer → Handles HTTP requests  
- Service Layer → Business logic  
- Repository Layer → Database operations  
- Entity Layer → Data models  

---

## 📧 OTP Verification

- Generates a random 6-digit OTP  
- Sent to student email  
- Valid for 5 minutes  
- Stored temporarily in memory  

---

## ⚠️ Limitations

- Admin login uses hardcoded credentials  
- OTP stored in memory (not scalable)  
- No JWT/session-based authentication  

---

## 🔮 Future Enhancements

- Implement JWT authentication  
- Role-based authorization (Admin/Student)  
- Store OTP in Redis or database  
- Generate attendance reports (PDF/Excel)  

---

## ▶️ How to Run

1. Clone the repository  
2. Configure MySQL in `application.properties`  
3. Add your email credentials for OTP  
4. Run the Spring Boot application  
5. Open browser and access the app  

---

## 💡 Author
Muthu Lakshmi
