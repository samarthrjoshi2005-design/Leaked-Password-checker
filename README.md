# Leaked Password Checker

A Python + SQLite tool that checks if a password has appeared in known data breaches, and scores its password strength.

## Features
- Hashes passwords using SHA-1 before comparing (never stores plain text)
- Looks up hashes against a local SQLite database of known leaked passwords
- Scores password strength (Weak / Medium / Strong) based on length, character variety
- Simple command-line interface

## How to run
  bash
python password_checker.py
  


## Tech used
- Python
- SQLite (sqlite3 module)
- hashlib (for hashing)
