#  Habit Tracker (CLI Project)
This is a command-line Habit Tracker built with Python using Object-Oriented Programming principles. It allows users to add habits, mark them as completed for the day, and view all tracked habits. Habit data is saved and loaded from a JSON file.

---

## Features:
- Add a new habit with a title and frequency.
- Mark a habit as "done" (only once per day).
- View all habits and their completion history.
- Persistent data storage using `habits.json`.
- Custom error handling (e.g., marking a habit that's already done today).
- Clean structure using:
  - OOP (`Habit` class)
  - File handling (`FileHandler` class)
  - Custom exceptions (`errors.py`)

---

## Project Structure:
├── main.py                # CLI logic and main loop
├── habit.py               # Habit class (with to_dict/from_dict, mark_done)
├── file_handler.py        # FileHandler class (load/save JSON)
├── errors.py              # Custom exception classes
├── habits.json            # Data file (auto-generated)


##  Features:
- Add a habit
- Mark a habit as done
- View all habits
- Save/load habits using JSON
- Uses custom errors and classes


## How to Run:
1. Make sure you have Python 3 installed.
2. Open your terminal and navigate to the project folder.
3. Run the program:
```bash
python main.py
