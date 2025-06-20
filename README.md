# mypro

📚 Library Management System – Java Console App
A simple and modular Library Management System built using Java. This console-based application demonstrates core Object-Oriented Programming (OOP) principles including encapsulation, inheritance, and abstraction. It allows authenticated users to add, view, and delete books, with role-based access for admins and regular users.

✅ Features
🧑‍💻 User authentication (login system)
🗂️ Book management: Add, view, and delete
🧑‍⚖️ Admin vs User roles with permission control
🔁 Console-based interactive menu
🧩 Clean, modular code using OOP concepts
📁 Project Structure & File Description
MainApp.java
The entry point of the application.
Handles user login and menu navigation.
Calls appropriate methods from LibraryManager based on user actions.
LoginManager.java
Manages user authentication.
Contains a list of predefined users.
Verifies login credentials and returns the authenticated User object.
User.java
Represents a user with a username, password, and role (admin or user).
Used to implement role-based access control.
Book.java
Represents a book with attributes like title, author, and bookId.
Contains constructors, getters, setters, and a toString() method.
LibraryManager.java
Core class for library operations.
Manages a list of books with functions to:
Add a new book (admin only)
View all books
Delete a book (admin only)
🧠 Concepts Used ✅ Object-Oriented Programming Classes, Objects, Inheritance, Encapsulation ✅ Role-Based Access Control ✅ Java Collections ArrayList for managing books ✅ Clean separation of concerns

🔧 Future Enhancements (Ideas 💡) 🗃️ Add file/database persistence (save books between sessions) 🎨 GUI using Swing or JavaFX 📊 Book search and filter options 🧪 Unit tests using JUnit

🙋‍♂️ Author Developed by Sairaj Gupta – Passionate Java developer and problem solver.
