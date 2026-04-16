🏦 Online Banking System (Full Stack Application)

A secure and scalable Online Banking System built using the Spring ecosystem.
This application enables users to manage accounts, perform transactions, and allows admins to monitor and control system operations.

🚀 Features
👤 User Portal
🔐 Secure login & registration (Spring Security)
💰 Deposit & withdraw funds
📊 View account details & balance
📜 Transaction history tracking
🏦 Banking Operations
🔄 Secure fund transfers
⚡ Real-time transaction updates
📈 Account balance management
🛠️ Admin Portal
👥 Manage users & accounts
📊 Monitor transactions
⚙️ Control system operations
🛠️ Tech Stack
Backend: Spring Boot, Spring Security, Spring Data JPA
Frontend (User): Thymeleaf, HTML, CSS, Bootstrap, jQuery
Frontend (Admin): Angular, TypeScript
Database: MySQL
ORM: Hibernate
Build Tool: Maven
🔐 Security
Spring Security authentication & authorization
Session management
Protection against common web vulnerabilities (XSS)
📂 Project Structure
banking-system/
│
├── controller/        # REST Controllers
├── service/           # Business logic
├── repository/        # JPA Repositories
├── model/             # Entity classes
├── security/          # Security configuration
├── config/            # App configuration
└── frontend/          # Thymeleaf + Angular UI
🔑 Key Functional Modules
User Management
Account Management
Transaction Processing
Admin Dashboard
⚙️ Setup Instructions
1️⃣ Clone Repository
git clone https://github.com/your-username/banking-system.git
cd banking-system
2️⃣ Configure Database
spring.datasource.url=jdbc:mysql://localhost:3306/banking_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
3️⃣ Run Application
mvn spring-boot:run
🧪 Testing
Use Postman to test backend APIs
Access UI via browser for user/admin portals
🎯 Highlights
Full-stack architecture with separate user & admin portals
Secure backend using Spring Security
Clean layered architecture (Controller → Service → Repository)
Scalable and modular design
💡 Future Enhancements
📱 Mobile app integration
💳 Payment gateway integration
📊 Advanced analytics dashboard
☁️ Microservices architecture
👨‍💻 Author

Lohith Krishna Killamsetty
Java Full Stack Developer

⭐ Contribution

Feel free to fork and contribute!

📜 License

This project is open-source and available under the MIT License.
