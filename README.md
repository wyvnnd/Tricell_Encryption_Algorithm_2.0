# Tricell_Encryption_Algorithm_2.0
This repository contains a visual representation of the Tricell Encryption Algorithm 2.0 in form of a Mermaid diagram. The encryption method was originally made for the university course "Introduction to IT".

## How it works
The encryption is made up of the message with salt/padding as prefix and suffix with the amount specified in the key. 
Spaces are replaced with underscores to make it harder to brute force. 
The last number in the key is a hexadecimal that is added to the characters unicode value.

> [!TIP]
> By shifting the message with the right amount to make it appear with a different alphabet makes it harder for AI (2026) to crack it.

The algorithm was made to be easy enough to decipher with instructions, but hard enough to keep unwanted people from cracking it, including AI.

## Credits
* Kelbel Khela (Emet-Selch, Nova & Phos)
