# To-Do List App (Console-based)

A simple command-line to-do list manager built in Python. Tasks are saved to `tasks.txt` so they persist between runs.

## Features
- View all tasks
- Add a new task
- Remove a task by number
- Tasks stored in a plain text file (`tasks.txt`)

## How to Run
```bash
python todo.py
```

Make sure `todo.py` is run from a folder you have write access to — it will automatically create `tasks.txt` there on first use.

## Usage
1. Run the script.
2. Choose an option from the menu:
   - `1` → View tasks
   - `2` → Add task
   - `3` → Remove task
   - `4` → Exit
3. Your tasks are saved automatically after every add/remove, so nothing is lost when you exit.

## Files
| File | Description |
|------|--------------|
| `todo.py` | Main application script |
| `tasks.txt` | Auto-generated storage file (created on first run) |

## Requirements
- Python 3.x (no external libraries needed)