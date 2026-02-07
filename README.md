# 📊 Employee Salary

## 📌 Project Description

This is a simple Java console application that calculates and manages the salary of an employee.
The program reads basic employee information such as name, gross salary, and associated tax or deduction values, then performs salary adjustments based on business rules.

This project reinforces core Java concepts including:

* Object-Oriented Programming (OOP)
* Class and object structure
* Encapsulation and validation
* Arithmetic operations
* User input handling

---

## 🛠️ Technologies Used

This project is implemented using:

* Java (JDK 17 or newer)
* Standard Java libraries (`java.util.Scanner`, etc.)

No external dependencies are required.

---

## 🚀 Functional Requirements

The program performs the following steps:

1. Asks the user to enter the employee’s name.
2. Reads the employee’s gross salary.
3. Applies adjustments or calculations as required (deductions, increases, net salary computation).
4. Displays the final calculated salary and related information.

The logic can include:

* Salary adjustments based on tax or specific allowance rules
* Updates to salary according to business conditions
* Output formatting to a user-friendly format

---

## 🧠 How It Works

At a high level:

* A `Scanner` object is used to read input from the console.
* A custom `Employee` or similar class holds the employee’s data.
* Business logic is encapsulated inside class methods that calculate final salary.
* The main class (`Program.java`) coordinates input, processing and output.

---

## 📦 Project Structure

```
EmployeeSalary/
├── src/
│   ├── application/
│   │   └── Program.java
│   └── entities/
│       └── Employee.java
├── .gitignore
├── README.md
└── workspace files
```

---

## 🧪 Example Usage

```
Enter employee name: John Doe
Enter gross salary: 4500.00
Enter tax value: 500.00

Employee: John Doe
Gross Salary: $ 4500.00
Tax: $ 500.00
Net Salary: $ 4000.00
```

---

## ⚙️ Behavior & Logic

* Uses a class to represent an employee and encapsulate salary details.
* Uses arithmetic operations and conditional logic to compute salary deductions or increases.
* Uses formatted output (`System.out.printf`) to display results with two decimal places.

---

## 🧑‍💻 Learning Goals

By completing and understanding this project, you will:

* Learn to define and instantiate classes
* Handle user input with `Scanner`
* Manipulate numeric values and format output
* Understand basic salary calculation logic in real-world scenarios
* Structure a Java project with multiple packages

---

## 📈 Possible Enhancements

You can extend this project further by:

* Adding validation for user input
* Supporting bonus and overtime calculations
* Allowing multiple employees to be processed
* Storing results in files
* Applying inheritance for different employee types

---

## 📄 License

This project is open source and available on GitHub.

