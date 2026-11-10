Student Management System (C++)

 Project Overview

The Student Management System is a simple console-based application developed in C++. It allows users to manage student records by adding new students, displaying all student information, and searching for a student using their roll number.

This project is designed for beginners to understand the basic concepts of C++ programming, including structures, arrays, loops, conditional statements, and user input/output.

 Features

- Add Student: Add a new student by entering their roll number, name, and marks.
- Display Students: View the records of all added students.
- Search Student: Search for a specific student using their roll number.
- Exit: Close the application safely.

 Technologies Used

- Programming Language: C++
- Library: iostream
- Data Structure: Structure ("struct") and Array
- Interface: Command-Line Interface (CLI)

 Project Structure

Student-Management-System/
│
├── main.cpp
└── README.md

 How to Run the Project

Step 1: Clone the Repository

git clone https://github.com/your-username/Student-Management-System.git

Step 2: Navigate to the Project Folder

cd Student-Management-System

Step 3: Compile the Program

Using GCC:

g++ main.cpp -o student

Step 4: Run the Program

On Windows:

student.exe

On Linux/macOS:

./student

 Program Menu

When you run the application, the following menu appears:

--- Student Management System ---
1. Add Student
2. Display Students
3. Search Student
4. Exit
Enter choice:

 Example Usage

--- Student Management System ---
1. Add Student
2. Display Students
3. Search Student
4. Exit
Enter choice: 1

Enter Roll Number: 101
Enter Name: Ali
Enter Marks: 85

Student Added Successfully!

--- Student Management System ---
1. Add Student
2. Display Students
3. Search Student
4. Exit
Enter choice: 2

Roll: 101
Name: Ali
Marks: 85

 Concepts Implemented

This project demonstrates the following C++ concepts:

- Structures ("struct")
- Arrays
- Variables and Data Types
- Loops ("do-while", "for")
- Conditional Statements ("if-else")
- User Input and Output ("cin", "cout")
- Searching using Linear Search
- Boolean Variables

 Limitations

- The system can store a maximum of 100 students.
- Student records are stored temporarily in memory.
- Data is lost when the program is closed.
- Student names are currently entered as single words.
- The system does not support updating or deleting student records.

Future Improvements

- Add student record deletion.
- Add student record updating.
- Support full names with spaces.
- Save student records in a file.
- Prevent duplicate roll numbers.
- Add input validation.

