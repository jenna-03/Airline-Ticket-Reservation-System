# **Airline Ticket Reservation System**

This project is an online air ticket reservation system developed as part of the NYU Tandon School of Engineering's Intro to Databases (CS-UY 3083) course. The system allows customers to search for flights, purchase tickets, and view flight statuses, while airline staff can manage flights, airplanes, and view customer data.

## **Features**

### **Customer Features:**
- **Search for Flights:** Search for one-way or round-trip flights based on source/destination cities or airports.
- **Purchase Tickets:** Buy flight tickets and view both future and past flights.
- **Rate and Comment:** Provide ratings and comments on past flights.
- **Track Spending:** Monitor spending over a specified period.

### **Airline Staff Features:**
- **Manage Flights:** Create, update, and manage flights and airplane details.
- **Flight Status:** View and manage flight statuses.
- **Customer Details:** Access customer information and flight ratings.
- **Reports:** Generate reports on frequent customers and revenue.

## **Technologies Used**

### **Backend:**
- **PHP:** Handles the server-side logic.
- **Python/MySQL:** Manages the relational database.

### **Frontend:**
- **HTML/CSS:** Structures and styles the web pages.
- **JavaScript:** Adds interactivity to the web pages.

## **Database Schema**
The database schema was designed and normalized based on an Entity-Relationship (ER) diagram to support complex queries and ensure data integrity. It includes tables for customers, airline staff, flights, tickets, airplanes, and airports.

## **Installation**

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-repo-link
    ```

2. **Navigate to the project directory:**
    ```bash
    cd your-repo-link
    ```

3. **Set up the database:**
    - Import the SQL schema from `database/schema.sql` into your MySQL database.

4. **Configure the database connection:**
    - Update the database configuration in `config/database.php` with your MySQL credentials.

5. **Start the server:**
    - Use a local server like XAMPP or WAMP to run the PHP application.

## **Usage**

### **Customer Operations:**
- **Register and Log In:** Register and log in as a customer.
- **Search for Flights:** Search for flights and purchase tickets.
- **Manage Bookings:** View and manage your bookings.

### **Airline Staff Operations:**
- **Log In:** Log in as an airline staff member.
- **Manage Flights:** Create and manage flight details.
- **Update Flight Statuses:** View and update flight statuses.

## **Security**

- **User Authentication:** Implemented using PHP sessions to ensure secure login and session management.
- **Prepared Statements:** Used in PHP to prevent SQL injection attacks.
- **HTTPS:** Ensures encrypted data transmission.

## **Contributing**

Contributions are welcome! Please fork the repository and create a pull request with your changes.
