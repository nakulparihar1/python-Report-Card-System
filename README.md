# Student Report Card Management System

A Python-based console application to manage student report cards with features such as adding students, validating marks, generating grades, saving/loading data, and logging activities.

## 📌 Features

* Add student marks with validation (0–100)
* Auto-calculate total, percentage, and grade
* Enforce minimum passing marks per subject
* Search students by name
* Display formatted individual or all reports
* Save and load records using JSON
* Log all major actions with timestamps

## 📂 Project Structure

* **main()** – Controls the application menu and flow
* **input_student()** – Collects student info with validation
* **evaluate_student()** – Calculates total, percentage, and grade
* **enforce_min_pass()** – Forces fail if any marks < 33
* **print_report()** – Prints a formatted report card
* **save_to_file() / load_from_file()** – Handle JSON storage
* **log_event()** – Appends activity logs to a text file

## 🛠️ Future Improvements

* Add CSV export
* Introduce GUI
* Add ranking system
* Include subject-wise analysis

## 📄 License

This project is open-source and free to use.
