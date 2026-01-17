🏦 Internet Banking Management System - Java Web Application -JSP_SERVELET_JDBC
-A secure and user-friendly web-based banking application developed using Java, JSP, Servlets, JDBC, and MySQL. This system enables customers and administrators to efficiently manage banking operations such as account handling, transactions, and authentication in a real-world banking workflow.

📌 Features:

👤 User Module:

Secure user registration and login

View account details and balance

Deposit and withdrawal operations

Transaction history tracking

Session-based authentication

🛠 Admin Module:

Create and manage customer accounts

View and monitor all transactions

Manage users and account details

Secure admin authentication

🏗 System Architecture:

Frontend: JSP, HTML, CSS

Backend: Java Servlets

Database: MySQL

Connectivity: JDBC

Architecture Pattern: MVC (Model-View-Controller)

🧰 Technologies Used

Java (Core, OOP)

JSP & Servlets

JDBC

MySQL

HTML, CSS

Apache Tomcat

Git & GitHub

⚙️ Setup & Installation:

🔹 Prerequisites
JDK 8+
Apache Tomcat 9+
MySQL Server
Eclipse / IntelliJ IDEA / NetBeans

🔹 Steps to Run the Project:
Clone the Repository
git clone https://github.com/surbhidubey21/internet-banking-management-system.git
Import Project into IDE
Eclipse: File → Import → Existing Projects into Workspace
IntelliJ: File → Open → Select project folder
Configure Database
CREATE DATABASE banking_system;
Import the provided .sql file (if available).
Update Database Credentials
Modify database config file:
String url = "jdbc:mysql://localhost:3306/banking_system";
String user = "root";
String password = "your_password";
Add MySQL Connector JAR
Ensure mysql-connector-j.jar is added to project libraries.

Configure Tomcat Server
Attach project to Apache Tomcat.

Run Application
Right-click project → Run on Server

Open in browser:

bash
Copy code
http://localhost:8080/internet-banking-management-system
🔐 Security Features

Input validation and exception handling

Session-based authentication

Secure database access using PreparedStatements

📊 Future Enhancements

Password encryption using BCrypt

OTP-based authentication

Fund transfer between accounts

Role-based access control

REST API integration
👩‍💻 Developer

Surbhi Dubey
🔗 GitHub: https://github.com/surbhidubey21

🔗 LinkedIn: https://www.linkedin.com/in/surbhi-dubey-03897b284/

📜 License

This project is for educational and academic purposes only.
