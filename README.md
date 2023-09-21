# Airline_Reservation_System_java

The Airline Reservation System is a Java-based application for managing airline-related operations, such as customer management, flight management, ticket booking, and more. This system provides a user-friendly interface implemented using Java Swing for the front-end and MySQL for the back-end database management.

## Features

- **User Authentication:** Secure login for administrators to access the system.
- **Customer Management:** Add, search, and view customer information.
- **Flight Management:** Add and view flight details, including arrivals, departures, and fares.
- **Ticket Booking:** Book tickets for customers, calculate fares, and manage bookings.
- **Ticket Retrieval:** Search and retrieve booked tickets by ticket ID.
- **Admin Management:** Add new administrators to the system.

### Prerequisites

- Java Development Kit (JDK)
- MySQL Database Server
- JDBC Driver for MySQL
- Apache NetBeans or another Java IDE (Integrated Development Environment)

### How to Run the Application
1. Clone or download the project files from the repository.
2. Open the project in your Java development environment (e.g., NetBeans, Eclipse).
3. Set up a MySQL database and update the database connection details in the code.
4. Import the required MySQL JDBC driver as a dependency.
5. Build and run the application from your development environment.

### Project Structure
- src/ - Contains the source code files.
- com.airline/ - Main package for the Airline Reservation System.
- model/ - Contains the model classes for customers, flights, and tickets.
- dao/ - Contains the Data Access Object (DAO) classes for database interactions.
- ui/ - Contains the user interface classes implemented using Java Swing.
- lib/ - Contains external libraries or dependencies.
- README.md - This file, providing an overview of the project.
