# Cloned Netflix

## Overview
**Cloned Netflix** is a Java-based application for managing student-related data. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations using Java object-oriented principles. 

The application provides functionalities to manage students, including adding, updating, deleting, and saving student data. The persistent storage is implemented through serialization, ensuring data is retained between sessions.

---

## Features
- Add new student information.
- Modify existing student details.
- Delete student records.
- Display all student data.
- Save and load data using serialized files.

---

## Project Structure
### **Source Files**
- **`Main.java`**  
  Entry point of the application. Manages user interactions and invokes functionality.
  
- **`Functionality.java`**  
  Contains core methods for handling student data:
  - Add, update, delete students.
  - Save and load serialized data.
  
- **`Student.java`**  
  Represents the `Student` entity with the following attributes:
  - Name
  - Age
  - Roll Number  
  Includes utility methods for displaying student details and generating unique identifiers.

### **Data File**
- **`studentdata.dat`**  
  Stores serialized student information for persistent storage.

---

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/knightrider-GH/netflix-clone>
