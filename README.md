Land Rental and Return System
This project is a Land Rental and Return System developed in Python for TechnoNepal, allowing users to rent and return lands stored in a text file. The system features:

User-friendly CLI (Command Line Interface) for renting and returning lands.

Invoice generation for transactions (saved in .txt files).

Real-time updates of land availability in the database (table.txt).

Error handling to validate user inputs (names, phone numbers, lease periods, etc.).

Modular design with separate Python files (main.py, read.py, write.py, operations.py) for better maintainability.

Key Features
✔ Rent Land: Users can rent available lands by providing details (name, phone, address, lease duration).
✔ Return Land: Users can return rented lands, with automatic fine/refund calculations for early/late returns.
✔ View Land Details: Displays all land records without requiring a transaction.
✔ Persistent Storage: Land data is stored in table.txt, and invoices are saved as .txt files.

Technologies Used
Python (Core logic, file handling)

Plain Text Files (table.txt for land data, custom files for invoices)

How It Works
Run main.py to start the system.

Choose options:

Rent land (marks land as Unavailable).

Return land (updates status to Available).

View land details.

Invoices are generated and saved automatically.

Ideal for small-scale land management, this project demonstrates Python fundamentals, file handling, and modular programming.
