# Discount Calculator

A simple Python program that calculates the final price of an item after applying a discount, with a minimum discount threshold requirement.

## Features

- Calculates final price after discount
- Applies discount only if it's 20% or higher
- User-friendly input prompts
- Formatted output with clear messaging
- Input validation (via float conversion)

## How It Works

### Function: `calculate_discount(price, discount_percent)`

This function takes two parameters:
- `price` (float): The original price of the item
- `discount_percent` (float): The discount percentage to apply

**Logic:**
- If discount percentage is 20% or higher:
  - Calculates discount amount: `price * (discount_percent / 100)`
  - Returns final price: `price - discount_amount`
- If discount percentage is less than 20%:
  - Returns the original price unchanged

### User Interaction

1. Program prompts for original price
2. Program prompts for discount percentage
3. Calls `calculate_discount()` function
4. Displays appropriate message based on whether discount was applied


## How to Run

1. Save the code to a file (e.g., `discount_calculator.py`)
2. Run the program:
   ```bash
   python discount_calculator.py
