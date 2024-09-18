# Employee Management System using PHP and MySQL

This is a simple **Employee Management System** developed using **PHP** and **MySQL**. It allows users to manage employee data by performing basic CRUD (Create, Read, Update, Delete) operations. The system is designed to help companies or HR teams efficiently manage and store employee information like name, gender, email, department, and address.

## Features
- **Search Employee**: Find employee records by their unique ID.
- **Add Employee**: Save new employee records with details like name, gender, email, department, and address.
- **Update Employee**: Modify existing employee details.
- **Delete Employee**: Remove employee records from the database.
- **Reset Form**: Clear all input fields.

## Technologies Used
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL

## How to Use
1. **Search Employee**: Enter the employee ID in the search field to load their data into the form.
2. **Add Employee**: Fill out the form fields and click "Save" to add a new employee to the database.
3. **Update Employee**: Search for the employee by ID, modify the fields, and click "Update" to save changes.
4. **Delete Employee**: Search for the employee by ID and click "Delete" to remove the employee from the database.
5. **Clear Form**: Click "Clear" to reset the form fields.

## Installation Instructions
1. Clone or download the project repository.
2. Set up a MySQL database and create a database named `employee`.
3. Create a table called `form` with the following structure:
   ```sql
   CREATE TABLE form (
       id INT AUTO_INCREMENT PRIMARY KEY,
       emp_name VARCHAR(100),
       emp_gender VARCHAR(50),
       emp_email VARCHAR(100),
       emp_department VARCHAR(100),
       emp_address TEXT
   );
   ```
4. Update the `connection.php` file with your database credentials (server, username, password).
5. Run the project on a local server like **XAMPP** or **WAMP**.
6. Access the application through `localhost/your-project-directory/`.

## Screenshots
- **Search Employee**: Allows searching employee by ID.
- **Add Employee**: Form for adding new employee records.
- **Update Employee**: Modify existing records by searching for the employee ID.
- **Delete Employee**: Deletes employee data with confirmation.

## License
This project is open-source and available under the MIT License.
