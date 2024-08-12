
## Key Features

1. **Object-Oriented Design**:
   * `Change` class: Encapsulates customer details and coin denomination calculations.
   * `Client` class: Manages user interaction and program flow.

2. **Data Structures**:
   * Arrays: Used for storing customer records (`ArrayChange`).
   * Objects: Utilized for representing individual customer data.

3. **Coin Change Calculation**:
   * Calculates change for various coin denominations ($2, $1, 50 cents, 20 cents, 10 cents, 5 cents).
   * Supports multiple customer records.

4. **User Interface**:
   * Interactive menu system for user operations.
   * Options to add customers, search records, find largest/smallest amounts, and calculate totals.

5. **Modular Design**:
   * Clear separation of concerns between data management (`Change` class) and user interaction (`Client` class).
   * Easily extendable for additional features.

## Program Structure

1. `Change.java`:
   * Contains methods for storing, modifying, and retrieving customer data.
   * Implements logical calculations for coin denominations.

2. `Client.java`:
   * Contains the main method and user interaction menu.
   * Implements various operations like searching, displaying records, and calculating totals.

## Object-Oriented Principles Implemented

- Encapsulation
- Information Hiding
- Open/Closed Principle
- Precondition and Postcondition
- Use of Private Variables
- Accessor and Mutator Methods
- Helper Methods
- High Cohesion and Low Coupling

## How to Run

1. Ensure you have Java Development Kit (JDK) installed on your system.
2. Clone this repository to your local machine.
3. Open the project in an IDE like Apache NetBeans (Version 17 or above recommended).
4. Compile and run the `Client.java` file to start the program.

## User Guide

The program will guide you through the following steps:
1. Enter customer names and coin amounts.
2. Choose from various menu options to perform operations on the entered data.
3. View results of calculations and searches.
