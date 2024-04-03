Counting Organizations from Email Addresses 

The "Counting Organizations" project is a Python application designed to read mailbox data from a file (mbox.txt), count the number of email messages per organization (i.e., domain name of the email address), and store the counts in a SQLite database. The application then retrieves and displays the top organizations with the highest email counts.
Functionality

    Reads the mbox.txt file containing mailbox data.
    Extracts email addresses from the mailbox data.
    Parses the domain name from each email address.
    Counts the occurrences of each domain name.
    Stores the counts in a SQLite database.
    Retrieves the top organizations with the highest email counts.
    Displays the top organizations and their respective counts.

Dependencies

    Python 3.x
    SQLite3 (built-in with Python)
    Regular expressions (re module)

Usage

    Input File: Place the mbox.txt file in the same directory as the Python script.
    Run the Script: Execute the Python script in any Python environment (e.g., Jupyter notebook, command line).
    Input Filename: When prompted, enter the filename mbox.txt.
    View Output: The script will display the top organizations and their email counts.

Documentation Sections

    Overview: Brief summary of the project's purpose and functionality.
    Functionality: Detailed description of the project's features and operations.
    Dependencies: List of required software and libraries.
    Usage: Step-by-step guide on how to use the project.
