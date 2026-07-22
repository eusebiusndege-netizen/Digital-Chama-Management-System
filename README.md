# Digital Chama Management System

A full-stack web application developed to digitize the management of **Chamas** (community savings and investment groups). The system provides a secure platform for managing members, contributions, loans, repayments, meetings, and financial records, replacing manual record-keeping with an efficient digital solution.

> **Academic Project:** COMP1643 – Final Year Project
> **Institution:** University of Greenwich

---

## Project Overview

The Digital Chama Management System was designed to improve transparency, accountability, and efficiency in the management of Chama activities. It enables administrators and members to manage contributions, loan applications, repayments, meetings, and financial transactions through a centralized web-based platform.

---

## Features

### User Management

* Secure user registration and login
* Role-based access control
* Profile management
* Password encryption

### Member Management

* Register and manage members
* View member profiles
* Member activity tracking

### Contributions

* Record member contributions
* View contribution history
* Contribution reporting

### Loan Management

* Apply for loans
* Loan approval workflow
* Loan repayment tracking
* Outstanding balance calculation

### Meeting Management

* Schedule meetings
* Record meeting details
* View meeting history

### Notifications

* Member notifications
* Contribution reminders
* Loan repayment reminders

### Financial Management

* Transaction recording
* Financial reports
* Income and expenditure tracking

### Security

* Authentication and authorization
* Protected API routes
* Input validation
* Secure database interactions

---

## Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MySQL

### Tools

* Visual Studio Code
* XAMPP
* Postman
* Git
* GitHub

---

## Project Structure

```text
Digital-Chama-Management-System/
│── config/
│── controllers/
│── middleware/
│── models/
│── routes/
│── uploads/
│── public/
│── database/
│── Images/
│── server.js
│── package.json
│── package-lock.json
│── README.md
```

---

## Installation

### Prerequisites

* Node.js
* MySQL
* XAMPP (or another MySQL server)
* Git

### Clone the Repository

```bash
git clone https://github.com/eusebiusndege-netizen/Digital-Chama-Management-System.git
```

### Navigate to the Project

```bash
cd Digital-Chama-Management-System
```

### Install Dependencies

```bash
npm install
```

### Configure the Database

1. Create a MySQL database.
2. Import the provided SQL file.
3. Update the database connection settings in the configuration file.

### Start the Application

```bash
npm start
```

or

```bash
nodemon server.js
```

Open your browser and navigate to the configured local development URL.

---

## Screenshots

Create an **Images** folder in the repository and add screenshots of the application.

Example:

```text
Images/
├── login.png
├── dashboard.png
├── members.png
├── contributions.png
├── loans.png
├── meetings.png
├── reports.png
```

Display them in the README:

```markdown
## Login Page

![Login](Images/login.png)

## Dashboard

![Dashboard](Images/dashboard.png)

## Loan Management

![Loans](Images/loans.png)

## Contributions

![Contributions](Images/contributions.png)
```

---

## Learning Outcomes

This project strengthened my skills in:

* Full-stack web development
* RESTful API development
* Database design and management
* Authentication and authorization
* CRUD operations
* Software engineering principles
* Agile software development
* Git version control
* Secure web application development

---

## Future Improvements

* M-Pesa payment integration
* SMS notifications
* Email notifications
* Advanced analytics dashboard
* Mobile application
* Multi-Chama support
* Cloud deployment
* Two-factor authentication
* Automated report generation

---

## Academic Context

This project was completed as part of the **COMP1643 – Final Year Project** at the **University of Greenwich**. The objective was to design and implement a secure web-based system for recording and tracking Chama contributions and loans while improving financial transparency and operational efficiency.

---

## Author

**Eusebius Ndege**

Computer Science Graduate | Full-Stack Developer

* **GitHub:** https://github.com/eusebiusndege-netizen
* **LinkedIn:** https://www.linkedin.com/in/eusebius-ndege-78b1712b0

---

## License

This project was developed for academic purposes as part of the Bachelor of Science (Honours) in Computer Science programme at the University of Greenwich.

---

⭐ If you found this project interesting or useful, feel free to star the repository.
