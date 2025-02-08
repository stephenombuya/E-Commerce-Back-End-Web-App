# E-Commerce Back-End Web App

## Overview
This project is a robust and scalable back-end for an E-Commerce platform, built with Java and Spring Boot. It provides features such as user authentication, product management, shopping cart functionality, payment integration, and order history tracking.

## Technologies Used
- **Java**: Main programming language.
- **Spring Boot**: Framework for building RESTful APIs.
- **MySQL**: Database for product, order, and user data.
- **Spring Data JPA**: For ORM and database interactions.
- **Spring Security**: For user authentication and authorization.
- **Stripe/PayPal SDK**: For payment processing.
- **Swagger/OpenAPI**: For API documentation.

## Features
### 1. User Management
- User registration and login.
- Role-based access control (Admin, Customer).

### 2. Product Management
- CRUD operations for products and categories.
- Inventory management.

### 3. Shopping Cart
- Add and remove products from the cart.
- Update item quantities.

### 4. Checkout and Payment
- Secure checkout process.
- Integration with Stripe/PayPal for payments.

### 5. Order Management
- View past orders and their statuses.
- Track order history.

### 6. Wishlist
- Save products for future purchases.

### 7. Search and Filtering
- Search products by name, category, and price range.

### 8. Discounts and Promotions
- Manage coupon codes.
- Implement special promotions.

## Installation & Setup
### Prerequisites
- Java 17+
- MySQL Server
- Maven

### Steps to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/stephenombuya/E-Commerce-Back-End-Web-App
   ```
2. Configure MySQL database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Install dependencies:
   ```sh
   mvn clean install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

## API Documentation
After starting the application, access API docs at:
```
http://localhost:8080/swagger-ui/index.html
```

## Contribution
Contributions are welcome! Feel free to submit a pull request or open an issue.

## License
This project is licensed under the MIT License.

