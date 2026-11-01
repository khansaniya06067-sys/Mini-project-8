# Library Management System 📚📖

A modular, object-oriented Python application designed to manage library operations, including book inventory, member records, borrowing workflows, and automated data persistence using JSON storage.

---

## 🏗️ Project Architecture & File Structure

The project is structured following clean coding principles and separation of concerns:

* **`main.py`:** The entry point of the application; handles the user interface flow, menus, and user inputs.
* **`models.py`:** Defines the core data classes/structures (e.g., `Book`, `Member`, or transaction models) representing system entities.
* **`library_service.py`:** Contains the core business logic, handling operations like issuing/returning books, searching catalogs, and managing user actions.
* **`storage.py`:** Manages file input/output operations, serialization, and deserialization of records.
* **`data.json`:** Local persistent database file used to save and reload library data across sessions.

---

## 📋 Features

* **Book Catalog Management:** Add, view, search, and update books within the library system.
* **Member Management:** Register and track library members.
* **Borrowing & Returning Workflow:** Track issued books, due dates, and return statuses.
* **Data Persistence:** Automatically saves and loads all records using a local JSON backend (`data.json`) to prevent data loss between runs.
* **Modular Codebase:** Cleanly separates UI navigation, business logic, data models, and storage operations.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have **Python 3.x** installed on your machine.

### Running the Application
1. Clone the repository or download the project files (`main.py`, `models.py`, `library_service.py`, `storage.py`, `data.json`).
2. Open your terminal or command prompt inside the project directory.
3. Run the application using:
   ```bash
   python main.py
