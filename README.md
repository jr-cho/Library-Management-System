# Library Management System

## **Project Description**

This project simulates the implementation of a **Library Management System** in C++ as described in a test scenario. The system demonstrates object-oriented programming concepts such as inheritance, polymorphism, operator overloading, templates, dynamic memory allocation, and exception handling.

---

## **Test Scenario**

You are tasked with designing a **Library Management System** in C++ using object-oriented programming principles. Follow the project specifications below:

### **1. Class `Book`**
- **Private Data Members**:
  - `title` (string): Title of the book.
  - `author` (string): Author of the book.
  - `id` (int): Unique book ID.
  - `isAvailable` (bool): Book availability status.

- **Public Methods**:
  - Constructor to initialize the book details.
  - Getter and setter methods for each data member.
  - `borrowBook()`: Sets `isAvailable` to `false`.
  - `returnBook()`: Sets `isAvailable` to `true`.
  - Overload the `<<` operator to display book details.

---

### **2. Class `User`**
- **Private Data Members**:
  - `name` (string): Name of the user.
  - `id` (int): Unique user ID.
  - `borrowedBooks` (array or vector of `Book` objects): Books borrowed by the user.

- **Public Methods**:
  - Constructor to initialize user details.
  - Methods to borrow and return books.
  - `display()`: Prints user details.

---

### **3. Class `LibraryManager`**
- **Private Data Members**:
  - An array or vector of `Book` objects.
  - An array or vector of `User` objects.

- **Public Methods**:
  - Methods to add, search, and delete books.
  - Methods to add, search, and delete users.
  - Method to handle borrowing and returning books.

---

### **4. Inheritance and Polymorphism**
- Create a base class `Person` with common attributes such as `name` and `id`.
- Derive the `User` class from the `Person` class.
- Include at least one virtual function in the `Person` class for custom behavior in derived classes.

---

### **5. Exception Handling**
- Use exception handling to manage:
  - Invalid inputs.
  - Attempts to borrow unavailable books.

---

### **6. Dynamic Memory Allocation**
- Use pointers and dynamic memory allocation for creating and managing `Book` and `User` objects.

---

### **7. Function Templates**
- Implement a function template to search for books or users by various criteria, such as:
  - Book title.
  - Book ID.
  - User name.
  - User ID.
