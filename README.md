# Bank Management System (C++ | OOP | Vectors)

This is a simple Bank Management System implemented in C++ using Object-Oriented Programming (OOP) and STL Vectors.
The project demonstrates the core banking operations like adding accounts, removing accounts, deposit, withdraw, and displaying customer details, while keeping the code clean and modular.

Features

Create customers

Create accounts linked with customers

Deposit money

Withdraw money

Display all accounts

Search account by account number

Remove an account using account number

Uses OOP concepts: classes, objects, constructors, encapsulation, getters/setters

Uses STL Vector to store accounts dynamically

Classes and Responsibilities
1. customer Class

Stores customer details:

Name

Address

Phone number

Provides:

Constructor

Getters and setters

Display function

2. account Class

Represents a bank account:

Account number

Pointer to related customer

Balance

Provides:

Deposit

Withdraw

Display account info

Setters & getters

3. bank Class

Stores:

Bank name

A vector<account*> to store multiple accounts

Provides:

Add account

Remove account

Find account

Display all accounts

Technologies Used

C++

OOP (Encapsulation, Composition)

STL Vector

How to Run
Compile
g++ main.cpp -o bank

Run
./bank

Sample Output
amount deposited : 7000
amount withdraw : 4000
amount withdraw : 25000
ACC101 5000
warda hayatabad 0393984748227484
ACC102 7000
amna hayatabad 03382732892382
ACC103 10000
sana cantt 03298789718979
removed successfully
ACC101 5000
warda hayatabad 0393984748227484
ACC103 10000
sana cantt 03298789718979
