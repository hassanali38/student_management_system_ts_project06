# student_management_system_ts_project06

Welcome to the Student Management System (SMS)! This is a Node.js command-line application that helps manage student information, including course enrollment, tuition fees, and balance. The application uses `inquirer` for user interaction and `chalk` for styled console outputs.

### Features

- **Add Student:** Add new students with details such as name, courses, and available balance.
- **Remove Student:** Remove a student's details from the system.
- **Show Student Info:** Display detailed information about a specific student.
- **Update Student Info:** Update various details of a student, such as ID, courses, balance, and fee status.
- **Show List of Students:** Display a list of all students enrolled in the system.
- **Quit:** Exit the application.

### Prerequisites

Make sure you have Node.js installed on your system. You can download it from [Node.js official website](https://nodejs.org/).

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/student-management-system.git
    cd student-management-system
    ```

2. Install the necessary packages:

    ```bash
    npm install
    ```

### Usage

To use the Student Management System, you can run it directly using Node.js or via the NPX command.

### Running with Node.js

```bash
node index.js
```

### Running with NPX

```bash
npx student-management-system
```

### How to Use

1. The application will prompt you to select the desired operation:
  - Add Student
  - Remove Student
  - Show Student Info
  - Update Student Info
  - Show List of Students
  - Quit
2. Follow the prompts to enter or update information as required.

### Example

```bash
WELCOME TO STUDENT MANAGEMENT SYSTEM (SMS)

? Which operation do you want to perform? (Use arrow keys)
  Add Student
  Remove Student
  Show Student Info
  Update Student Info
  Show List of Students
  Quit
```

```bash
Enter the details of student 1:
Name: John Doe
Select the courses: [x] Programming Fundamentals in Python     ----- $50
                   [ ] Essentials of CyberSecurity            ----- $65
                   [x] Introduction to Machine Learning       ----- $35
Available Balance (In Dollars): 100
Autogenerated ID: 12345
Total Tuition Fee: $85
Tution Fee Paid Successfully!
Remaining Balance: $15
```

### Acknowledgements

1. [Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) for prompt interface
2. [Chalk](https://github.com/chalk/chalk) for styled console output

### Author
Hassan Ali

