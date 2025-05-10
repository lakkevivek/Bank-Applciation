
# 🏦 Java Full-Stack Banking Application

This is a simple full-stack banking system built with **Spring Boot** for the backend and **HTML/CSS/JavaScript** for the frontend. It allows users to create accounts, deposit and withdraw funds, view account details, and delete accounts.

---

## 🚀 Features

- ✅ Create a bank account
- 💰 Deposit money
- 💸 Withdraw money
- 👁️ View account details
- 🗑️ Delete account

---

## 🛠️ Tech Stack

**Frontend**  
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=fff)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=fff)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=fff)](https://getbootstrap.com/)

**Backend**  
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)](https://www.java.com/)

---

## 📁 Project Structure

\`\`\`
Java-Fullstack-Bank/
│
├── backend/
│   └── src/
│       └── main/
│           ├── java/com/example/bank/
│           │   ├── controller/
│           │   ├── model/
│           │   ├── repository/
│           │   └── BankApplication.java
│           └── resources/
│               ├── application.properties
│               └── static/  ← Frontend lives here
│                   ├── index.html
│                   ├── style.css
│                   └── script.js
│
├── pom.xml
└── README.md
\`\`\`

---

## 📦 Setup Instructions

1. **Clone the Repository**
   \`\`\`bash
   git clone https://github.com/your-username/Java-Fullstack-Bank.git
   cd Java-Fullstack-Bank
   \`\`\`

2. **Backend**
   - Open in your favorite IDE (e.g., IntelliJ, Eclipse)
   - Make sure \`Spring Web\`, \`Spring Data JPA\`, and \`H2 Database\` are added as dependencies.
   - Run the \`BankApplication.java\`.

3. **Access Frontend**
   - Spring Boot serves \`index.html\` from \`src/main/resources/static/\`
   - Open \`http://localhost:8080\` in your browser.

---

## 📝 License

This project is licensed under the MIT License.

---

## 🤝 Contributions

Pull requests are welcome! For major changes, please open an issue first.
