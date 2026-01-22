# CaesarCipher
A simple and efficient Python implementation of the Caesar Cipher. This script provides easy-to-use functions for encrypting and decrypting text using alphabet shifting, featuring case preservation and input validation.
Caesar Cipher in Python

A lightweight Python script to perform Caesar Cipher encryption and decryption. This implementation uses Python's built-in translation mapping to ensure fast performance while keeping the code readable and easy to use.
🚀 Features

    Bidirectional: Includes dedicated functions for both encryption and decryption.

    Case Sensitivity: Correctly handles both uppercase and lowercase letters.

    Symbol Preservation: Numbers, spaces, and special characters (like !, @, #) remain unchanged.

    Error Handling: Validates that the shift value is an integer between 1 and 25.

⚙️ How It Works

The Caesar Cipher is a type of substitution cipher where each letter in the original text is replaced by a letter a certain number of positions down the alphabet.

For instance, with a shift of 3:

    A becomes D

    B becomes E

    Z wraps around to become C

💻 Usage

    Clone the Repository:
    Bash

    git clone https://github.com/stellarmindz/CaesarCipher.git

    Run the Script: You can import the functions into your own project or use the provided example:
    Python

    from caesar_cipher import encrypt, decrypt

    # Encrypt a message
    secret = encrypt("Hello World!", 5)
    print(secret)  # Output: Mjqqt Btwqi!

    # Decrypt a message
    original = decrypt("Mjqqt Btwqi!", 5)
    print(original)  # Output: Hello World!

🛠️ Requirements

    Python 3.x (No external libraries required)
