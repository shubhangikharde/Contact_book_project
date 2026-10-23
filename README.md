
# Contact Book Management System

## Project Overview

The Contact Book Management System is a beginner-friendly, menu-driven Python project that helps users manage contact information. Users can create, view, update, and delete contacts through a command-line interface.

## Features

- **Create Contact:** Save a contact's name, phone number, and email address.
- **View Contacts:** Display saved contact details.
- **Update Contact:** Edit an existing contact's information.
- **Delete Contact:** Remove a selected contact.
- **Exit:** Close the application using the menu.

## Technologies Used

- **Python** — application logic and functions
- **JSON** — contact data serialization and storage
- **File Handling** — reads and writes contact data in `contact_info.txt`
- **Jupyter Notebook** — development environment (`.ipynb`)

## How It Works

1. The program displays a menu of available operations.
2. The user selects an operation.
3. Contact details are loaded from `contact_info.txt`.
4. When a contact is added, updated, or deleted, the program saves the changes to the file.
5. The user can continue using the menu or choose Exit.

## Requirements

- Python 3.x
- Jupyter Notebook, or Python to run the code after exporting it from the notebook

No third-party Python packages are required; the project uses Python's built-in `os` and `json` modules.

## How to Run

### Option 1: Using Jupyter Notebook

1. Open `contact_book_project.ipynb` in Jupyter Notebook.
2. Run the notebook cells in order.
3. Run the cell that calls `menu()`.
4. Follow the on-screen menu.

### Option 2: Using a Python Script

1. Export or copy the notebook code into a file named `contact_book.py`.
2. Open a terminal in that folder.
3. Run:

```bash
python contact_book.py
```

## Data Storage

Contact records are stored locally in `contact_info.txt` in JSON format. The file is created when contacts are saved. Keep this file to retain your saved contacts.

## Project Structure

```text
Contact-Book-Management-System/
├── contact_book_project.ipynb
├── contact_info.txt   # Created when contact data is saved
└── README.md
```

## Learning Outcomes

- Practiced Python functions and menu-driven programming.
- Used conditional statements and loops.
- Read and wrote files using Python.
- Stored and retrieved structured data using JSON.
- Implemented basic CRUD operations (Create, Read, Update, Delete).

## Limitations

- This is a command-line application, not a web or mobile app.
- Contact data is stored in a local file rather than a database.
- Input validation and error handling can be improved.

## Future Improvements

- Add stronger validation for phone numbers and email addresses.
- Handle invalid menu choices and non-numeric contact selections safely.
- Add contact search functionality.
- Add a graphical user interface or connect the project to a database.

## Author
Shubhangi Kharde
