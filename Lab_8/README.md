# Lab 8: Exception Handling and Logging in Python

## Overview

This lab focuses on implementing **robust error handling and logging mechanisms in Python applications**. Exception handling allows programs to gracefully handle runtime errors without crashing, while logging helps developers monitor application behavior and debug issues efficiently.

The lab demonstrates how to manage file operations, process JSON data safely, and implement both basic and advanced logging systems.

---

## Objectives

By completing this lab, you will learn how to:

* Implement `try/except` blocks to manage runtime errors
* Handle specific exceptions such as:

  * `FileNotFoundError`
  * `PermissionError`
  * `IOError`
  * `JSONDecodeError`
* Use `finally` blocks to ensure proper resource cleanup
* Implement file handling using context managers (`with` statement)
* Parse and validate JSON data
* Configure Python’s `logging` module
* Implement advanced logging with multiple handlers
* Build robust and reliable Python applications

---

## Lab Tasks

### Task 1: Basic Exception Handling for File Operations

This task demonstrates how to handle common file-related errors.

Key concepts:

* Opening and reading files
* Handling missing files
* Managing permissions
* Ensuring proper resource cleanup

Scripts included:

* `file_handler.py`
* `enhanced_file_handler.py`

---

### Task 2: JSON Exception Handling and Data Validation

This task focuses on processing JSON data while handling potential errors such as malformed JSON or missing data fields.

Key concepts:

* JSON parsing
* Error handling with `json.JSONDecodeError`
* Data validation
* Custom exception classes

Scripts included:

* `json_handler.py`
* `advanced_json_handler.py`

---

### Task 3: Logging Configuration for Application Monitoring

This task introduces logging systems that help track application behavior and detect runtime issues.

Key concepts:

* Logging levels (`DEBUG`, `INFO`, `WARNING`, `ERROR`, `CRITICAL`)
* Logging to console and files
* Rotating log files
* Structured logging format

Scripts included:

* `basic_logging.py`
* `advanced_logging.py`

---

## Project Structure

```
Lab08_Exception_Handling_Logging
│
├── file_handler.py
├── enhanced_file_handler.py
├── json_handler.py
├── advanced_json_handler.py
├── basic_logging.py
├── advanced_logging.py
│
├── example.txt
├── test_data.txt
├── special_chars.txt
│
├── valid_data.json
├── malformed_data.json
├── valid_user.json
├── invalid_user.json
├── wrong_types.json
```

---

## Running the Scripts

Run any script using Python:

```bash
python3 file_handler.py
```

Example:

```bash
python3 advanced_logging.py
```

---

## Example Output

Example console output when processing JSON files:

```
INFO - Starting JSON processing for: valid_user.json
INFO - Successfully processed JSON file: valid_user.json
ERROR - File not found: nonexistent.json
```

---

## Log Files Generated

When running the logging scripts, the following log files will be created:

```
logs/debug.log
logs/errors.log
logs/app_rotating.log
```

These logs help developers analyze system behavior and troubleshoot issues.

---

## Key Learning Outcomes

After completing this lab, students will be able to:

* Build reliable Python programs that handle runtime errors gracefully
* Debug applications effectively using logging
* Safely process structured JSON data
* Apply best practices for exception handling in real-world applications

---

## Author

**Sajid Imran**

IT Support | Cloud | Python | Data Science Enthusiast

---
