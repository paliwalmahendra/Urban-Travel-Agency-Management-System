# Urban Travel Agency Management System

## Overview
The Urban Travel Agency Management System is a C++ application designed to manage various aspects of a travel agency. The system includes functionality for managing customers, cabs, hotel bookings, and generating receipts for charges incurred by customers.

## Features
- **Customer Management**: Add and view customer details.
- **Cab Management**: Rent standard and luxury cabs, calculate costs based on distance, and hire cabs.
- **Booking Management**: Book hotel packages from partnered hotels.
- **Charges & Bill**: Generate and display receipts for customer transactions.

## Classes and Methods
### 1. `ManageMenu`
Handles the main menu and initial setup for the application.
- **Constructor**: Prompts for admin name and displays the main menu.

### 2. `Customer`
Manages customer details and records.
- `getDetails()`: Prompts the user to enter customer details and saves them to a file.
- `showDetails()`: Displays details of all previous customers.

### 3. `Cabs`
Handles cab rentals and cost calculations.
- `cabDetails()`: Displays cab options, calculates costs based on user input, and allows cab hiring.

### 4. `Booking`
Manages hotel bookings and packages.
- `hotels()`: Displays hotel options and packages, allows booking based on user input.

### 5. `Chargers`
Generates and displays receipts.
- `printBill()`: Generates a receipt and saves it to a file.
- `showBill()`: Displays the generated receipt.

## Usage
1. **Run the Application**: Compile and run the program using a C++ IDE or command line.
2. **Main Menu**: Choose options from the main menu to manage customers, cabs, bookings, and view charges.
3. **Customer Management**: Enter new customer details or view existing customer records.
4. **Cab Management**: Rent a standard or luxury cab and calculate travel costs.
5. **Booking Management**: Book hotel packages from available options.
6. **Charges & Bill**: Generate and display receipts for the transactions.

## Files
- **main.cpp**: Contains the source code for the application.
- **old-customers.txt**: Stores details of all customers.
- **receipt.txt**: Stores the receipt for the most recent transaction.

## Dependencies
- **C++ Standard Library**: Includes headers such as `<iostream>`, `<fstream>`, `<iomanip>`, and `<windows.h>`.

## How to Compile
1. Open the project in your preferred C++ IDE (e.g., CodeBlocks).
2. Compile and build the project.
3. Run the executable to start the application.

## Author
- **Your Name**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- IDE Used: CodeBlocks

Feel free to contribute to this project by forking the repository and submitting pull requests.
