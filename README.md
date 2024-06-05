# PRODIGY_CS_01
The Caesar Cipher is a classical encryption method that shifts each letter in the plaintext by a fixed number of positions up or down the alphabet. Users can input a message and a shift value to perform the encryption or decryption. This repository features a Python implementation of the Caesar Cipher algorithm, providing functionality for both encryption and decryption of messages.

Encryption:
To encrypt a message using the Caesar Cipher, you must first choose a shift value, k, which determines the number of positions each letter in the plaintext will be shifted. For each letter in the plaintext, if the character is an alphabetic character (uppercase or lowercase), it is shifted by k positions in the alphabet. If the shift moves past the boundaries of the alphabet, it wraps around to the beginning or end accordingly. Non-alphabetic characters remain unchanged.

Decryption:
To decrypt a message encrypted with the Caesar Cipher, use the same shift value, k, that was used for encryption. For each letter in the ciphertext, if the character is an alphabetic character (uppercase or lowercase), it is shifted by −k positions in the alphabet. If the shift moves past the boundaries of the alphabet, it wraps around to the beginning or end accordingly. Non-alphabetic characters remain unchanged.
