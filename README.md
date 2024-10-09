Password Strength Assessment Tool

This is a simple Python-based tool that evaluates the strength of a user's password based on various criteria, such as length, the presence of uppercase and lowercase letters, numbers, and special characters. The tool provides feedback to users on how to improve the strength of their passwords.

Features

Password Length Check: Ensures that the password has a minimum of 8 characters.
Uppercase and Lowercase Check: Verifies that the password contains both uppercase and lowercase letters.
Number Check: Checks if the password contains at least one numeric digit.
Special Character Check: Ensures the password has at least one special character (e.g., !@#$%^&*).
Feedback: Provides specific feedback to help users create stronger passwords.

How It Works
Users enter a password to assess.
The tool evaluates the password based on the following criteria:
Minimum length of 8 characters.
Presence of both uppercase and lowercase letters.
Presence of at least one number.
Presence of at least one special character.
Based on these factors, the password is rated as Strong, Moderate, or Weak, and specific feedback is provided to guide users in improving their password.

Usage
Clone the repository:

git clone https://github.com/irfanahmd1/PRODIGY_CS_3.git

Navigate to the project directory:

cd PRODIGY_CS_3

Run the tool:

python "password strength checker tool.py"
Enter a password when prompted, and receive feedback on its strength.

Example

Enter your password: Pass@123
Password Strength: Strong password!

For weaker passwords, the tool provides actionable feedback to help strengthen them.
