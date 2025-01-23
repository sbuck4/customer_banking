# Savings & CD Account Management

## Project Overview
This project creates a simple system to manage savings and CD (Certificate of Deposit) accounts. The system allows the user to create accounts, set an initial balance, interest rate, and maturity period (in months), and calculate the interest earned over that period. It then updates the account balances with the calculated interest and displays the updated values.

## File Structure
- **Account.py**: Contains the `Account` class, which models the basic structure of an account. This class includes methods to set the balance and interest.
- **cd_account.py**: Defines a function to create a CD account, calculate interest, and update the balance.
- **savings_account.py**: Defines a function to create a savings account, calculate interest, and update the balance.
- **main.py**: The main program that prompts the user for input, creates accounts, and displays the results.

## Key Classes and Functions

### `Account` Class (in `Account.py`)
- **`__init__(balance, interest)`**: Initializes an account with a given balance and interest rate.
- **`set_balance(balance)`**: Updates the account balance.
- **`set_interest(interest)`**: Updates the interest earned on the account.

### `create_savings_account(balance, interest_rate, months)` (in `savings_account.py`)
This function:
- Creates a savings account with the given balance and interest rate.
- Calculates the interest earned based on the number of months.
- Updates the balance of the savings account with the interest earned.
- Returns the updated balance and interest earned.

### `create_cd_account(balance, interest_rate, months)` (in `cd_account.py`)
This function:
- Creates a CD account with the given balance and interest rate.
- Calculates the interest earned based on the number of months.
- Updates the balance of the CD account with the interest earned.
- Returns the updated balance and interest earned.

### `main()` (in `main.py`)
- Prompts the user to input the initial balances, interest rates, and maturity periods for both savings and CD accounts.
- Calls the respective functions to calculate the interest and update the balances.
- Displays the interest earned and updated balances for both types of accounts.

## Usage Instructions

1. **Clone or download the repository** to your local machine.
   
2. **Run the `main.py` script**:
    ```bash
    python main.py
    ```

3. **Follow the on-screen prompts** to enter the following information:
   - Initial balance for the savings account.
   - Annual interest rate for the savings account.
   - Maturity period (in months) for the savings account.
   
   Then, the program will display the interest earned and the updated savings account balance.

4. Repeat the process for the CD account:
   - Initial balance for the CD account.
   - Annual interest rate for the CD account.
   - Maturity period (in months) for the CD account.
   
   The program will then display the interest earned and the updated CD account balance.
