# Module19_FinTech

## Languages and Technologies

Python: The main programming language used for writing the application code.
Streamlit: A Python library for creating interactive web applications.
Ganache: A personal Ethereum blockchain used for testing and development.
GitHub: The platform used for version control and repository hosting.


Here's a breakdown of the application's functionality:

## Step 1: Import Ethereum Transaction Functions

The crypto_wallet.py script contains Ethereum transaction functions that have been incorporated into Python functions, allowing automation of wallet operations.
The application reads the mnemonic seed phrase provided by Ganache from the SAMPLE.env file and renames it to .env.
The generate_account, get_balance, and send_transaction functions from crypto_wallet.py are imported into the fintech_finder.py file.
The generate_account function creates an HD wallet and Ethereum account for the Fintech Finder customer.

## Step 2: Sign and Execute a Payment Transaction

The customer selects a fintech professional from the drop-down menu and inputs the number of hours they want to hire the worker.
The application calculates the worker's wage based on the hourly rate from the candidate database and the hours worked.
The calculated wage is displayed on the Streamlit sidebar.
When the customer clicks the "Send Transaction" button, the application calls the send_transaction function with the customer's Ethereum account information, the candidate's address, and the wage value to send the payment.
## Step 3: Inspect the Transaction on Ganache

The application follows coding conventions and formatting standards, utilizing concise logic and adhering to DRY principles. It is well-commented to provide clarity and understanding to other developers.


## Conclusion
This application, Fintech Finder, provides a web interface for customers to interact with various Ethereum blockchain functionalities. It integrates two Python files, fintech_finder.py and crypto_wallet.py, to automate tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via the Ganache blockchain.
