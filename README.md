# Hospital-Appointment-Management-System

A full-stack Hospital Appointment Booking System built using **Spring Boot**, **Spring Security**, **JWT Authentication**, **PostgreSQL**, and **Swagger**. The system enables secure user registration, authentication, role-based authorization, doctor management, and appointment booking.

---

## 🚀 Features

### 👤 Authentication & Authorization
- User Registration
- JWT Authentication
- Secure Login
- Password Encryption using BCrypt
- Role-Based Access Control (RBAC)

### 👥 User Roles
- ADMIN
- DOCTOR
- PATIENT

### 🩺 Doctor Management
- Add Doctor
- View All Doctors
- View Doctor by ID
- Search Doctors by Specialization
- View Available Doctors

### 📅 Appointment Management
- Book Appointment
- View Appointment Details
- View Patient Appointments
- View Doctor Appointments
- Cancel Appointment

### 🔒 Security
- Spring Security
- JWT Token Authentication
- Endpoint Authorization
- BCrypt Password Encoding

### 📖 API Documentation
- Swagger UI
- OpenAPI Documentation

---

# 🛠️ Tech Stack

### Backend
- Java 21
- Spring Boot 3
- Spring Security
- Spring Data JPA
- Hibernate
- JWT
- MapStruct
- Lombok
- Maven

### Database
- PostgreSQL

### Documentation
- Swagger / OpenAPI

---

# 📂 Project Structure

```
src
│
├── appointment
├── authentication
├── common
├── config
├── department
├── doctor
├── exception
├── hospital
├── medicalrecord
├── notification
├── payment
├── review
├── schedule
├── security
├── token
├── user
├── util
└── websocket
```

---

# 🔑 User Roles

| Role | Permissions |
|------|-------------|
| ADMIN | Manage doctors, users, appointments |
| DOCTOR | View assigned appointments |
| PATIENT | Register, Login, Book Appointments |

---

# 📌 API Endpoints

## Authentication

| Method | Endpoint |
|---------|----------|
| POST | `/api/auth/login` |

---

## Users

| Method | Endpoint |
|---------|----------|
| POST | `/api/users/register` |

---

## Doctors

| Method | Endpoint |
|---------|----------|
| POST | `/api/doctors` |
| GET | `/api/doctors` |
| GET | `/api/doctors/{id}` |
| GET | `/api/doctors/specialization/{specialization}` |
| GET | `/api/doctors/available` |

---

## Appointments

| Method | Endpoint |
|---------|----------|
| POST | `/api/appointments` |
| GET | `/api/appointments` |
| GET | `/api/appointments/{id}` |
| GET | `/api/appointments/patient/{patientId}` |
| GET | `/api/appointments/doctor/{doctorId}` |
| PUT | `/api/appointments/{id}/cancel` |

---

# 🗄️ Database

- PostgreSQL
- Hibernate ORM
- Spring Data JPA

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/hospital-appointment-booking-system.git
```

```bash
cd hospital-appointment-booking-system
```

---

## Configure Database

Update `application.properties`

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/hospital_db
spring.datasource.username=postgres
spring.datasource.password=your_password
```

---

## Run Application

Using Maven

```bash
mvn spring-boot:run
```

or

Run

```
HospitalAppointmentBookingSystemApplication.java
```

---

# 📖 Swagger

After starting the application

```
http://localhost:8080/swagger-ui/index.html
```

---

# 🧪 Tested Functionalities

- ✅ User Registration
- ✅ JWT Login
- ✅ Role-Based Authorization
- ✅ Doctor APIs
- ✅ Appointment APIs
- ✅ PostgreSQL Integration
- ✅ Swagger Documentation

---

# 📈 Future Enhancements

- React Frontend
- Email Notifications
- Payment Gateway
- Medical Records Module
- Doctor Availability Scheduler
- WebSocket Notifications
- Docker Deployment
- CI/CD Pipeline
- Cloud Deployment (Render/AWS)

---

# 📸 Screenshots
<img width="1600" height="745" alt="image" src="https://github.com/user-attachments/assets/acaadd55-24e6-4aa2-b30c-a69912061020" />
<img width="1600" height="770" alt="image" src="https://github.com/user-attachments/assets/8d794bfb-a054-4686-a6c4-0904c40a3d37" />
<img width="1600" height="789" alt="image" src="https://github.com/user-attachments/assets/d1490468-c6d4-49f9-8bec-30b316868055" />
<img width="1600" height="682" alt="image" src="https://github.com/user-attachments/assets/6cd209b3-f261-4b1f-b746-168285b6dfd4" />



---

# 👨‍💻 Author

** Gurramkonda Sharun Prakash**

GitHub: https://github.com/sharunpg

LinkedIn: www.linkedin.com/in/sharun-prakash-gurramkonda-27459b25b

---

# ⭐ If you like this project

Give this repository a ⭐ on GitHub.
