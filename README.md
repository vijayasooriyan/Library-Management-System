# Library Management System
#### Video Demo: https://youtu.be/cFCleHb1-_c
#### Description:
The Library Management System is a comprehensive software solution designed to automate and manage various aspects of a library's operations. This system provides functionalities for managing admin profiles, staff members, and books, ensuring efficient and organized management of library resources.

## Features
- **Admin Profile Management**: Admins can add, edit, and delete their profiles to maintain updated information.
- **Staff Management**: Allows admins to manage staff details, including adding, updating, and removing staff members.
- **Books Management**: Facilitates the management of book records, including adding new books, editing existing book details, and removing books from the inventory.
- **User-Friendly GUI**: Built with Java Swing, the application offers an intuitive and interactive interface for users.
- **Database Integration**: Utilizes MySQL to store and manage data, ensuring data integrity and consistency.

## Project Structure
- **src/**: Contains the source code of the application, including all the Java files that implement the various functionalities of the system.
    - **com/library/**: Main package containing core classes for database connection and UI components.
- **build/**: Directory where compiled classes and build-related files are stored.
- **test/**: Contains unit tests for the application to ensure code quality and functionality.
- **build.xml**: Apache Ant build script used for automating the build process.
- **manifest.mf**: Manifest file containing metadata about the JAR file.
- **LIBRARY MANAGEMENT.jar**: Executable JAR file for the project.

## Getting Started
To set up and run the Library Management System on your local machine, follow these steps:

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache NetBeans IDE (or any other preferred IDE)
- MySQL Server

### Installation
1. **Clone the repository**:
    

2. **Open the Project**:
    - Launch Apache NetBeans IDE.
    - Navigate to `File > Open Project` and select the extracted project folder.

3. **Set Up the Database**:
    - Create a MySQL database named `library_management`.
    - Execute the SQL scripts provided in the `src/sql` directory to set up the necessary tables.

4. **Configure Database Connection**:
    - Update the database configuration in the `src/com/library/DatabaseConnection.java` file with your MySQL credentials.

### Running the Application
1. **Build the Project**:
    - In NetBeans, right-click on the project and select `Clean and Build`.

2. **Run the Application**:
    - Right-click on the project and select `Run`.

## Design Choices
While developing the Library Management System, several design decisions were made to ensure the robustness and usability of the application:

- **Database Choice**: MySQL was chosen for its reliability, ease of use, and widespread adoption, making it a suitable choice for managing library data.
- **GUI Framework**: Java Swing was used to create a responsive and interactive user interface, providing a better user experience.
- **Modular Structure**: The application was designed with a modular structure, separating different functionalities into distinct classes and packages to enhance maintainability and scalability.

## Conclusion
The Library Management System is a robust and user-friendly application designed to streamline library operations. By automating tasks related to admin profiles, staff management, and book inventory, this system aims to improve the efficiency and organization of libraries.

