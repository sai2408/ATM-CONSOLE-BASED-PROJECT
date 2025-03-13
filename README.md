# ATM System

This is a simple ATM System implemented in Python that allows users to perform basic banking operations such as withdrawal, deposit, pin generation, and mini statement. The program uses a dictionary to simulate user accounts with basic account details.

## Features

1. **Withdrawal**: Allows users to withdraw money from their account, provided they enter the correct PIN and have sufficient funds.
2. **Deposit**: Users can deposit money into their account.
3. **Pin Generation**: Allows users to generate a new PIN if they don't already have one associated with their account.
4. **Mini Statement**: Displays account details like account holder's name, account number, date of birth, and balance.

## How to Run

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/atm-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd atm-system
    ```

3. Run the script using Python:

    ```bash
    python atm_system.py
    ```

## Code Structure

- **accounts**: A dictionary that stores account information. Each account is represented by an account number, which is associated with a list containing:
    - User Name
    - Date of Birth (in `dd-mm-yyyy` format)
    - Account Balance
    - Pin (None if not set)
  
- **dobm**: A dictionary mapping month numbers to month names to display the user's birth month in a readable format.

## Example Interaction

### Withdrawal
