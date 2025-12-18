A robust, console-based Python application that simulates the core functionalities of an Automated Teller Machine. This project demonstrates fundamental software engineering principles including secure authentication workflows, state management, and robust error handling.

🚀 Features
Secure Authentication: Multi-level login system requiring a valid username and a 4-digit PIN.

Transaction Management: Supports real-time cash deposits and withdrawals with automated balance updates.

Account Services: Users can perform balance inquiries and view their current account status.

Security Protocols:

Limited login attempts (max 3) to prevent unauthorized access.

PIN change functionality with requirements for 4-digit complexity and mismatch verification.

Error Handling: Validates user inputs for "PIN mismatch," "Insufficient funds," and "Invalid responses" to ensure system stability.

🛠️ Technical Stack
Language: Python 3.x

Modules: getpass (for secure PIN entry), os, string

Logic: Implementation of iterative loops, nested conditional statements, and list-based data persistence.

📋 How to Use
Run the script:

Bash

python atm.py
Login: Enter one of the pre-configured usernames (e.g., user2) and the corresponding PIN (e.g., 2222).

Navigate Menu:

Enter w to Withdraw cash.

Enter l to Lodge (Deposit) cash.

Enter p to change your PIN.

Enter q to Quit the session.

💻 Code Structure
The application uses a modular logic flow:

User Validation: A while loop continuously checks for valid usernames and manages login attempts.

Transaction Logic: Calculations for balance updates are performed instantly upon successful input validation.

Security Checks: Checks for digit-only PIN inputs and ensures new PINs differ from old ones.
