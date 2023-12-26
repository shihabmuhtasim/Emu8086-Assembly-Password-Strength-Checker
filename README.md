# Emu8086 Assembly Password Strength Checker
An Assembly language project utilizing the emu8086 processor to assess password strength based on length, character types, username existance and sequences. Categorizes passwords as Very Strong, Strong, Weak, or Very Weak.
![GitHub top language](https://img.shields.io/github/languages/top/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?color=f5f5dc)
![GitHub language count](https://img.shields.io/github/languages/count/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?color=f5f5dc)
![GitHub last commit](https://img.shields.io/github/last-commit/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?color=f5f5dc)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?color=f5f5dc)
![GitHub repo size](https://img.shields.io/github/repo-size/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?color=f5f5dc)
![GitHub watchers](https://img.shields.io/github/watchers/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker?style=social)

![NUMERICAL METHODS (1)](https://github.com/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker/assets/92597456/7f236831-3aed-4d65-ac65-a60172bb9694)

## Description

This password strength checker, implemented in Assembly language for the emu8086 processor, evaluates the strength of a password based on the following criteria:

1. Minimum length of 6 characters.
2. At least one special character.
3. At least one digit.
4. At least one uppercase letter.
5. At least one lowercase letter.
6. No three same characters in a row (e.g., 111, 222).
7. No three sequentially increasing inputs (e.g., 123, abc).
8. The username of the user can't exist in the password.

The output declaration is as follows:

1. If all 7 criteria are fulfilled: Very strong password.
2. If 5 or 6 criteria are fulfilled: Strong password.
3. If 3 or 4 criteria are fulfilled: Weak password.
4. If 0, 1, or 2 criteria are fulfilled or the length is less than 6 or username exists in password: Very weak password.

![output picture](https://github.com/shihabmuhtasim/Emu8086-Assembly-Password-Strength-Checker/assets/92597456/f270ebd1-9fc6-4ed5-b1c3-aca018ceafaf)


## Usage

Simply run the provided Assembly code on an emu8086 processor to check the strength of a password.

## How to Run

1. Load the code into an emu8086 processor.
2. Run the program.

The program will prompt you to insert a password and then output the password strength based on the defined criteria.

## Contributors

- [github.com/shihabmuhtasim] 

## License


For any questions or feedback, feel free to contact [shihabmuhtasim@gmail.com].

Happy coding!
