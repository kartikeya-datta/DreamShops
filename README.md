# 🛍️ DreamShops – Full Stack E-Commerce Platform
Developed a comprehensive e-commerce application featuring user authentication, product management, and shopping cart functionalities


DreamShops is a full-featured e-commerce web application built using React.js and Spring Boot. It empowers users to seamlessly browse products, efficiently manage their shopping carts, and securely complete purchases. For administrators, a dedicated dashboard provides comprehensive control over inventory, categories, and user accounts.

### 👤 User

* **Register/Login with JWT Authentication:** Secure user authentication using JSON Web Tokens.
* **Browse products by category:** Easily navigate through products organized into relevant categories.
* **Add/Remove items from the shopping cart:** Intuitively manage items within the shopping cart.
* **Checkout with order summary:** Review and confirm orders with a detailed summary before purchase.

### 🛠️ Admin

* **Manage product listings (Add, Edit, Delete):** Full control over the product catalog.
* **Upload images and manage product categories:** Easily manage product visuals and organizational structure.
* **Role-based access control:** Securely manage different levels of administrative privileges.
* **View all registered users:** Gain insights into the user base.

### 💡 Additional Highlights

* **Fully responsive and mobile-friendly UI:** Provides a seamless experience across various devices.
* **Protected API routes using Spring Security:** Ensures secure communication between frontend and backend.
* **Optimized database queries using Hibernate:** Enhances application performance and efficiency.
* **Clean modular architecture for scalability:** Designed for easy expansion and maintenance.

## 🧱 Tech Stack

| Frontend    | Backend       | Database   | Security           | Dev Tools             |
| ----------- | ------------- | ---------- | ------------------ | --------------------- |
| React.js    | Spring Boot   | MySQL      | JWT, Spring Security | Postman, Git, Maven   |
| Redux Toolkit | Spring Data JPA |          | Role-Based Access  | IntelliJ, VS Code     |
|             | Hibernate     |          |                    |                       |

## 📸 Screenshots

**[Include a few UI screenshots here for better engagement]**

* Home page with product grid
* Shopping cart summary
* Admin dashboard
* Login/Register screens

## 🛠️ Setup Instructions

### 🔧 Backend (Spring Boot)

```bash
cd backend
mvn clean install
mvn spring-boot:run