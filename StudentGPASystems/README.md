# Student GPA Management System

## Description
The **Student GPA Management System** is a Python-based console application that allows users to manage student records, including adding, editing, deleting, and finding students. The system also calculates the average GPA of all students in the database. The program reads and writes student data from a text file.

## Features
- **List Students**: Display all student records.
- **Add Student**: Add a new student with name, ID, and GPA.
- **Edit Student**: Modify an existing student's details.
- **Delete Student**: Remove a student from the database.
- **Find a Student**: Search for a student by ID.
- **Calculate GPA Average**: Compute the average GPA of all students.
- **Persistent Storage**: Saves student records in a text file.

## Requirements
- Python 3.x
- A text file to store student data

## Installation
1. Clone or download this repository.
2. Ensure Python 3.x is installed on your system.
3. Create a text file with student records in the format:
   ```
   John Doe,101,3.5
   Jane Smith,102,3.8
   ```

## Usage
1. Run the script:
   ```sh
   Ass3_final.py
   ```
2. Enter the filename containing student data when prompted.
3. Choose from the menu options to perform various student record operations.
4. Follow the prompts to input required data.
5. Enter **Q** to quit the application.

## File Format
Each student record is stored in a CSV-like format:
```
<Student Name>,<Student ID>,<GPA>
```
Example:
```
Alice Johnson,103,3.6
```

## Functions Overview
- `print_menu()`: Displays the main menu and returns the user's choice.
- `format_student(s)`: Formats student data for storage.
- `display_std_header()`: Prints a formatted header for displaying students.
- `display_student(s)`: Displays a single student's details.
- `find_student(students, id)`: Searches for a student by ID.
- `list_students(students)`: Lists all students.
- `add_student(file_name, students)`: Adds a new student.
- `edit_student(id, students)`: Edits an existing student's information.
- `delete_student(s, students)`: Deletes a student from the list.
- `calculate_average(students)`: Computes the average GPA.
- `load_students(file_name)`: Loads students from a text file.
- `update_students(file_name, students)`: Updates the text file with student records.
- `main()`: Runs the main program loop.

## Example Run
```
*************************************************************
          *** Welcome to Students GPA Systems! ***
*************************************************************
Select from the following options
L- List Students
A- Add Student
E- Edit Students
D- Delete Student
F- Find A Student
G- GPA Average
Q- Quit
>>> L
=============================================================
    Student Name       Student ID              GPA
=============================================================
      John Doe              101               3.50
     Jane Smith             102               3.80
```

## Contributors
- Thu Duong Nguyen 
- Stanlee Fabian 

## License
This project is for educational purposes only.

