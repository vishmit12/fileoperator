📔 Personal Journal Manager

A simple Personal Journal Manager built with Python. This project allows users to create, view, search, and delete journal entries using a text file for storage.

🎥 Demo Video

▶️ Watch Project Demo
https://drive.google.com/file/d/1sXGhqgwBO0Rhm9glMPP7HlSKj-3Y03a8/view?usp=drivesdk

✨ Features

➕ Add a new journal entry

📖 View all journal entries

🔍 Search entries using keywords

🗑️ Delete all journal entries

🕐 Store the date and time of each entry

💾 Save journal entries permanently in a text file

⚠️ Handles invalid user input and file errors

🛠️ Technologies Used

Python 3

datetime — for date and time

os — for file management

File Handling — for storing journal entries

match-case — for menu selection

📂 Project Structure
Personal-Journal-Manager/
│
├── journal.py
├── demo.txt
└── README.md

🚀 How to Run
1. Clone the repository
git clone YOUR_GITHUB_REPOSITORY_LINK

2. Open the project folder
cd Personal-Journal-Manager

3. Run the Python program
python journal.py

📋 Menu Options

When the program starts, you will see:

========== Personal Journal ==========
1. Add Entry
2. View All Entries
3. Search Entry
4. Delete All Entries
5. Exit

1️⃣ Add Entry

Allows the user to write and save a new journal entry.

Example:

Enter your journal here: Today I learned Python file handling.


The entry is stored in demo.txt along with the current date and time.

2️⃣ View All Entries

Displays all previously saved journal entries.

Example:

[2026-10-01 13:10:20] Today I learned Python file handling.
[2026-10-01 15:30:12] I practiced Python classes.

3️⃣ Search Entry

Allows the user to search for a specific keyword.

Example:

Enter the keyword you want to find: Python


The program displays entries containing that keyword.

4️⃣ Delete All Entries

Allows the user to delete the complete journal file after confirmation.

Are you sure you want to delete all entries (yes/no):

5️⃣ Exit

Closes the journal manager.

💾 Data Storage

The journal entries are stored in:

demo.txt


The program uses append mode ("a") so that adding a new entry does not overwrite previous entries.

🧠 Concepts Learned

This project demonstrates several important Python concepts:

Classes and Objects

Functions and Methods

File Handling

Exception Handling

try-except

with open()

Lists

String Methods

Date and Time

os module

match-case

User Input

🔮 Future Improvements

Some possible improvements for future versions:

🔐 Add password protection

✏️ Edit existing journal entries

📅 Search entries by date

🗂️ Organize entries into categories

🖥️ Create a GUI using Tkinter

🗄️ Store entries in SQLite instead of a text file

🔒 Encrypt private journal entries

👨‍💻 Author

Your Name

If you found this project useful, feel free to ⭐ the repository!

📜 License

This project is created for learning and educational purposes.