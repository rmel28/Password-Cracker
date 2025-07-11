# Password Hash Cracker (Educational Use Only)

This Python script demonstrates a basic dictionary attack on a hashed password using the MD5 hashing algorithm. It is intended for educational purposes to help students understand how hashing and password cracking techniques work in cybersecurity.

## Disclaimer

This project is for educational purposes only.  
Do not use it against systems, data, or services without proper authorization.  
It is intended to promote ethical learning and awareness of password security risks.

## Overview

- Hashes a known password using MD5
- Reads a list of leaked passwords from a file
- Encodes each word and hashes it using MD5
- Compares the hashed values to find a match
- Demonstrates the concept of a dictionary attack

## Files

- `password_cracker.py` — main Python script
- `Ashley-Madison.txt` — example password list (can be downloaded from [SecLists](https://raw.githubusercontent.com/danielmiessler/SecLists/master/Passwords/Leaked-Databases/Ashley-Madison.txt))

## How to Use

1. Install Python 3 if you don’t have it already
2. Download or copy the wordlist file
3. Update the `password_filename` variable in the script to match the path to your wordlist
4. Run the script:

```bash
python3 password_cracker.py 
