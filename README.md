# Contact-Management--System
# Contact Management System

A Python-based CLI application to perform fundamental CRUD (Create, Read, Update, Delete) operations for contact management.

## 📌 How It Works (Project Logic)
1. **Data Structure:** The project stores records in an in-memory **Python Dictionary** (`contacts = {}`).
   - The contact's **Name** serves as the unique Key.
   - The value is an inner dictionary containing attributes like `phone` and `email`.
2. **Operations Supported:**
   - **Create:** Adds new contacts via standard console input.
   - **Read:** Enables $O(1)$ fast lookup using dictionary keys and displays formatted details.
   - **Delete:** Safely removes entries using Python's `del` keyword after verifying the key exists.
3. **Control Flow:** Driven by a continuous `while True` loop that presents an interactive menu and routes user selections to modular functions.

## 🛠️ Technical Stack
- **Language:** Python 3
- **Concepts:** Functions, Dictionary (Hash Map), Control Flow, Exception/Boundary Checks

## 💻 How to Run
```bash
python main.py
