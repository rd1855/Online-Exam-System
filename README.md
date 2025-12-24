# Online Examination Portal

**A secure, full-stack web application for conducting online aptitude and technical assessments with automated evaluation.**

![Project Banner](https://via.placeholder.com/1200x400/007bff/ffffff?text=Online+Examination+Portal)  
*(Replace with your own screenshot/banner after deployment)*

**Live Demo:** [Coming Soon – Deployed on Render/Railway]  
**Date:** June 2025  
**Status:** Portfolio Project – Actively Maintained

### Tech Stack
- **Backend**       : Python + Flask  
- **Database**      : MySQL (with SQLAlchemy ORM)  
- **Frontend**      : HTML5, CSS3, JavaScript (Vanilla + Bootstrap 5)  
- **Authentication** : JWT (JSON Web Tokens) + bcrypt password hashing  
- **Other**         : RESTful API design, Jinja2 templating, responsive design

### Key Features
- **Role-based Access Control**  
  Admin → Create/edit/delete exams & questions  
  Student → Register, login, take exams, view results  

- **Exam Management (Admin)**  
  - CRUD operations for exams and MCQ questions  
  - Question bank with options + correct answer marking  
  - Optional: question randomization (planned)

- **Student Exam Experience**  
  - View available exams  
  - Real-time countdown timer with auto-submit  
  - One question at a time (or all-at-once option)  
  - Prevent basic cheating (tab switch detection, disable right-click – JS based)

- **Automatic Scoring & Results**  
  - Instant evaluation for objective (MCQ) questions  
  - Detailed result page: score, correct/incorrect answers, performance summary  
  - Result history per student

- **Security Best Practices**  
  - JWT-based stateless authentication  
  - Passwords hashed with bcrypt  
  - Parameterized queries → protection against SQL injection  
  - Input validation & sanitization → protection against XSS  
  - Role-based route protection

### Project Structure
