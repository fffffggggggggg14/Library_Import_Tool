# clsTools Library 🔧

A comprehensive C++ utility library providing essential tools for randomization, array manipulation, encryption, and user input handling.

## Features ✨
- *Randomization*: Generate random numbers, characters, words, and keys
- *Swapping*: Swap values of different data types
- *Shuffling*: Shuffle arrays of numbers, strings, and characters
- *Array Filling*: Fill arrays with random values (numbers, strings, characters, and keys)
- *Encryption & Decryption*: Simple text encryption and decryption using a shift key
- *User Input Handling*: Securely read numbers, strings, and boolean values with validation
- *Validation*: Check if a number is within a specified range

## Installation 📥
1. Include the following file in your project:
```cpp
#include "clsTools.h"

Quick Start 🚀

// Initialize random seed
clsTools::Srand();

// Generate a random number between 1 and 100
int randomNum = clsTools::RandomNumber(1, 100);
cout << "Random Number: " << randomNum << endl;

// Generate a random uppercase letter
char randomChar = clsTools::RandomChar(clsTools::CapitalLetter);
cout << "Random Uppercase Letter: " << randomChar << endl;

// Encrypt and decrypt a text
string encrypted = clsTools::EncryptText("Hello", 3);
cout << "Encrypted: " << encrypted << endl;

string decrypted = clsTools::DecryptText(encrypted, 3);
cout << "Decrypted: " << decrypted << endl;

Main Functions 🔑

Advanced Examples 📚

1. Generating Random API Keys

string apiKey = clsTools::KeyRandomLetter(clsTools::CapitalLetter);
cout << "API Key: " << apiKey << endl;
// Example output: "XGHT - BDKS - YWLP - ZFQR"

2. Filling and Shuffling an Array

int arr[10];
clsTools::FillArrayWithRandomNumbers(arr, 10, 1, 50);
clsTools::ShuffleArray(arr, 10);

3. Validating User Input

int age = clsTools::ReadNumber("Enter your age (18-60): ", 18, 60);
cout << "Your age is: " << age << endl;

Integration with Other Libraries 🔗

Can be used alongside clsString for advanced text processing

Works well with clsDate for random date generation and formatting


Technical Notes 💡

1. Random Seed: Always call clsTools::Srand() before using random functions for better randomness.


2. Case Sensitivity: Random character generation differentiates between uppercase and lowercase letters.


3. Performance: Optimized for handling large arrays and text operations efficiently.



Contribution 🤝

Contributions are welcome! Please follow these guidelines:

1. Add tests for each new function.


2. Maintain a consistent coding style.


3. Document all changes in English.



License 📄

This project is licensed under the MIT License.


---

Developed with ❤️ by Mohamed Essam | GitHub

This documentation maintains clarity, provides examples, and ensures easy usability for developers. Let me know if you need any modifications!
