# Hospital-Management-System
# 🏥 Hospital Management System

A backend-based Hospital Management System built using **Spring Boot** that manages patients, doctors, appointments, and insurance details efficiently using REST APIs.

---

## 🚀 Features

* 👨‍⚕️ Doctor Management (Add, View, Update)
* 🧑‍🤝‍🧑 Patient Management
* 📅 Appointment Scheduling System
* 🏥 Department Management
* 💉 Insurance Handling
* 📊 Blood Group Statistics
* 🔄 RESTful API architecture

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** (Add MySQL / H2 depending on your setup)
* **Build Tool:** Maven
* **Architecture:** Layered Architecture (Controller, Service, Repository)
* **Tools:** IntelliJ IDEA, Postman

---

## 📁 Project Structure

```
hospitalManagementSystem/
│
├── Controller/
├── Service/
├── Repository/
├── Entity/
├── DTO/
├── resources/
│   ├── application.properties
│   └── data.sql
```

---

## ⚙️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/pallavi123-gif/Hospital-Management-System.git
```

2. Navigate to the project folder:

```
cd Hospital-Management-System
```

3. Run using Maven:

```
mvn spring-boot:run
```

4. Access APIs via Postman:

```
http://localhost:8080/
```

---

## 📌 API Endpoints (Sample)

| Method | Endpoint      | Description       |
| ------ | ------------- | ----------------- |
| GET    | /doctors      | Get all doctors   |
| POST   | /patients     | Add new patient   |
| GET    | /appointments | View appointments |

---

## 🧪 Testing

* Unit tests included using Spring Boot Test
* Run tests using:

```
mvn test
```

---

## 🔮 Future Enhancements

* 🔐 JWT Authentication & Authorization
* 👥 Role-Based Access (Admin/Doctor/Patient)
* 🗄️ MySQL Integration
* 📄 Swagger API Documentation
* 🌐 Frontend Integration (React/Angular)

---

## 👩‍💻 Author

**Pallavi Malekar**
📧 [2430012@ritindia.edu](mailto:2430012@ritindia.edu)

---

## ⭐ Show your support

If you like this project, please ⭐ the repository!

