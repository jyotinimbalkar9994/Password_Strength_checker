# 🔐 Password Strength Checker

A simple **Python-based Password Strength Checker** that evaluates the strength of a password based on common security requirements. It provides instant feedback and suggests improvements to help users create stronger passwords.

## 📌 Project Overview

The Password Strength Checker is a command-line application developed using Python. It checks whether a password meets several security conditions, including:

* Minimum **8 characters**
* At least **one number**
* At least **one uppercase letter**
* At least **one lowercase letter**
* At least **one special character**

Based on these conditions, the program provides feedback such as **Weak**, **Medium**, or **Strong**.

## ✨ Features

* 🔢 Checks for numbers/digits
* 🔠 Checks for uppercase letters
* 🔡 Checks for lowercase letters
* 🔣 Checks for special characters
* 📏 Validates minimum password length
* 💬 Provides clear feedback to the user
* 🔄 Allows multiple password checks in one session
* 🚪 Supports an `exit` command to quit the program
* 🐍 Built entirely with Python

## 🛠️ Technologies Used

* **Python 3**
* **Regular Expressions (`re`)**
* String methods
* Conditional statements
* Functions
* Loops

## 📂 Project Structure

```text
Password-Strength-Checker/
│
├── password_checker.py
└── README.md
```

## ⚙️ Password Strength Rules

| Requirement          | Description                                   |
| -------------------- | --------------------------------------------- |
| 📏 Length            | Password must contain at least 8 characters   |
| 🔢 Number            | Must contain at least one digit               |
| 🔠 Uppercase         | Must contain at least one uppercase letter    |
| 🔡 Lowercase         | Must contain at least one lowercase letter    |
| 🔣 Special Character | Should contain at least one special character |

### Strength Levels

* **Weak** → Password does not meet the basic security requirements.
* **Medium** → Password meets the basic requirements but can be improved with special characters.
* **Strong** → Password satisfies all required conditions.

## 🧠 How It Works

The program uses a function called `check_password_strength()` to validate the password.

The function checks the password in the following order:

1. Checks whether the password contains at least 8 characters.
2. Checks for at least one numeric digit.
3. Checks for at least one uppercase letter.
4. Checks for at least one lowercase letter.
5. Uses a regular expression to check for special characters.
6. Returns an appropriate strength message.

The `password_checker()` function handles user input and allows the user to repeatedly test passwords until they enter `exit`.

## 🔒 Security Note

This project is intended for **learning and demonstration purposes**. It provides a basic password-strength check and should not be considered a complete password-security solution.

For real-world applications, passwords should be handled securely using appropriate password hashing algorithms and should **never be stored or logged as plain text**.

## 📚 Learning Outcomes

Through this project, you can practice:

* Python functions
* `if` conditions
* `while` loops
* String manipulation
* Regular expressions
* User input handling
* Basic password-security concepts

## 🔮 Future Improvements

Possible improvements include:

* Add a graphical user interface (GUI)
* Add a password strength score
* Check passwords against common-password lists
* Add a password generator
* Hide password input using `getpass`
* Provide more detailed strength recommendations
* Add unit tests
* Improve special-character validation
* Add entropy-based password strength estimation

## 👨‍💻 Author

**Jyoti Nimbalkar**

If you found this project useful, consider ⭐ starring the repository!

---

### 📄 License

This project is open-source and available for educational purposes.
