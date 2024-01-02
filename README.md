# Employee Management System

The full-stack application is a robust employee management system designed for seamless interaction and efficient handling of employee data. Utilizing React for the frontend, users can easily navigate through a well-organized interface that displays a comprehensive list of employees. The frontend allows for the addition of new employees, enabling users to input relevant details and seamlessly submit the information. To ensure data accuracy and real-time updates, the application leverages Spring Boot on the backend. This powerful framework manages server-side operations, facilitating smooth communication between the frontend and the MySQL database employed for data storage. The system not only supports the addition of new employees but also provides functionality for updating existing employee information and removing employees when necessary. Overall, this full-stack application ensures a user-friendly experience, leveraging the strengths of React, Spring Boot, and MySQL to deliver a dynamic and efficient employee management solution.

# Prerequisites

Before running the project, ensure you have the following prerequisites:

Node.js 12.18.2: The project requires Node.js version 12.18.2. Please ensure you have this version installed.
Database Configuration: Update the application.properties file in the Spring Boot backend according to your database configuration. Make sure to set the correct values for the database URL, username, password, etc. This ensures proper connectivity with your MySQL database. 

<strong>Database Configuration</strong><br>
spring.datasource.url=jdbc:mysql://your-database-url:3306/your-database-name
spring.datasource.username=your-database-username
spring.datasource.password=your-database-password

Ensure that the database specified in the URL exists, and the provided credentials have the necessary permissions.


# API Documentation

1. Get All Employees
Endpoint: GET /api/v1/employees
Description: Retrieve a list of all employees in the system.
2. Create Employee
Endpoint: POST /api/v1/employees
Description: Add a new employee to the system. Send a POST request with the employee details in the request body.
3. Get Employee by ID
Endpoint: GET /api/v1/employees/{id}
Description: Retrieve details of a specific employee by providing their ID in the endpoint.
4. Update Employee
Endpoint: PUT /api/v1/employees/{id}
Description: Update details of a specific employee by sending a PUT request with the updated information in the request body.
5. Delete Employee
Endpoint: DELETE /api/v1/employees/{id}
Description: Delete a specific employee by sending a DELETE request with the employee's ID.
Usage

Make requests to the respective endpoints using tools like curl or through your preferred API client.
Ensure proper error handling, especially when dealing with non-existing employees.
Replace {id} with the actual ID of the employee you want to interact with.
Feel free to explore and utilize these endpoints to manage your employee data effectively. If you have questions or encounter issues, refer to this documentation or seek assistance.

Happy managing! 🚀