# Create-User Script  

### Author: Quan Nguyen  
### Program Creation Date: 11/3/2024  
### Program Last Updated Date: 11/6/2024  

This Python script automates the process of creating user accounts, setting passwords, and assigning users to groups on a Linux-based system. It processes input data in a specific format and uses system commands to manage user accounts and groups.

---

## Overview  

This script:  
1. Reads input from the standard input (`sys.stdin`).  
2. Validates each line of input using regular expressions and a specific format.  
3. Creates user accounts using the `adduser` command.  
4. Sets user passwords.  
5. Assigns users to specified groups.  

---

## Script Details  

### Dependencies  
The script uses the following Python modules:  
- **`os`**: Used for executing system commands (commented out in this version).  
- **`re`**: Used for pattern matching with regular expressions.  
- **`sys`**: Used to access standard input.  
