# CS313 INTERMEDIATE COMPUTER PROGRAMMING Spring 2024 – MIDTERM EXAM (PROJECT ASSESMENT)

# Author
- Julia Mc-Addy

# Task
My task is to implement a simplified banking system that models the behavior of bank accounts. This 
project will test my knowledge and skills in various C++ concepts, including copy constructors, multiple inheritance, 
operator overloading, range-based loops, standard template library (STL), and virtual functions. I will also be 
required to design and implement a class hierarchy for different types of bank accounts.

# Project Requirements
1. Class Hierarchy:
    - Created a base class called BankAccount with the following attributes:
      - std::string accountNumber
      - std::string accountHolderName
      - double balance
    - Implemente the following member functions for the BankAccount class:
        - A default constructor.
        - A parameterized constructor that takes accountNumber, accountHolderName, and balance as parameters.
        - A copy constructor.
        - A virtual function void deposit(double amount) that adds amount to the balance.
        - A virtual function void withdraw(double amount) that subtracts amount from the balance.
        - A virtual function void display() const that displays the account information (account number, account holder name, and balance).
2. Derived Classes:
    - Created two derived classes, SavingsAccount and CheckingAccount, both inheriting from BankAccount.
    - SavingsAccount had an additional attribute double interestRate and a member function void addInterest() that increases the balance by the interest rate times the current balance.
    - CheckingAccount had an additional attribute double overdraftLimit and override the withdraw function to allow for overdrafts up to the overdraft limit.
3. Operator Overloading:
  - Implemented the + operator overloading for BankAccount objects to combine the balances of two accounts and return a new BankAccount object.
4. STL Usage:
  - Used a STL vector to store and manage a collection of BankAccount objects.
5. Range-Based Loops:
  - Used range-based loops to iterate through and display the information of all the accounts in your container.

# External Resources
Lake, R. (2023a, April 10). Which bank has the best overdraft limit?. Chime. https://www.chime.com/blog/which-bank-has-the-best-overdraft-limit/ 

This was used to understand the concept of overdraft limit

# Software used
DEV C++

# How to compile and run my program.
1. Open DEV C++
2. Open the file (BankAccount.cpp). Ensure it has the .cpp extension. The file should have been in a "Project" and the option "Console Application" should have been selected. 
3. Go to "Execute"
4. Go to "Compile & Run"
5. The output is displayed in the console
