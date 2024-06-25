# Expense-Tracker-with-Data-Visualization

This Expense Tracker is a command-line interface (CLI) application written in Python. It allows users to log daily expenses and visualize expenses by category or over time.

## Features

- Log expenses with date, category, amount, and description.
- Visualize expenses by category using bar charts.
- Visualize daily expenses over time using line charts.

## Requirements

- Python 3.x
- pandas
- matplotlib

## Installation

1. Clone the repository or download the `expenses.py` script.
2. Ensure you have Python 3.x installed on your system.
3. Install the required Python packages using the following command:
   ```bash
   pip install pandas matplotlib
   ```

## Usage

1. Run the script using Python:
   ```bash
   python expenses.py
   ```
2. Follow the on-screen prompts to log expenses or visualize expense data.

## Code Description

### `expenses.py`

This script provides a simple CLI for managing and visualizing personal expenses. The script uses pandas for data manipulation and matplotlib for generating charts.

#### Functions

- **`initialize_csv()`**: Initializes the CSV file with headers if it does not exist.
- **`log_expense()`**: Logs a new expense entry to the CSV file.
- **`load_expenses()`**: Loads expense data from the CSV file into a pandas DataFrame.
- **`visualize_expenses_by_category(df)`**: Generates a bar chart of expenses by category.
- **`visualize_expenses_over_time(df)`**: Generates a line chart of daily expenses over time.
- **`main()`**: Main function to handle user interaction and execute the appropriate actions based on user input.

#### Contact
For any questions or suggestions, please contact Shobhit Kasturey at shobhitkasturey@gmail.com.

---

