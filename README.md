# Test Case Samples

Test Case 1: Valid Credentials

**Description**
Verify that users with valid credentials can successfully log in.

**Steps to Reproduce:**
1. Navigate to the login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click on the "Login" button.

**Expected Result:**
The user should be logged in and directed to the home page or a dashboard.

**Test data:**
User: radu & pass:123456


*******************************************

Test Case 2: Invalid Username

**Description:**
Ensure that users with an invalid username cannot log in.

**Steps to Reproduce:**
1. Navigate to the login page.
2. Enter an invalid username.
3. Enter a valid password.
4. Click on the "Login" button.

**Expected Result:** 
The system should display an error message indicating that the username is not recognized.

**Test data:**
User: radum & pass:123456


*******************************************

Test Case 3: Invalid Password

**Description:**
Verify that users with an invalid password cannot log in.

**Steps to Reproduce:**
1. Navigate to the login page.
2. Enter a valid username.
3. Enter an invalid password.
4. Click on the "Login" button.

**Expected Result:**
The system should display an error message indicating that the password is incorrect.

**Test data:**
User: radu & pass:1234567


*******************************************

Test Case 4: Empty Username and Password Fields

**Description:** 
Ensure the system handles empty username and password fields appropriately.

**Steps to Reproduce:**
1. Navigate to the login page.
2. Leave the username field empty.
3. Leave the password field empty.
4. Click on the "Login" button.

**Expected Result:**
The system should display appropriate error messages for both empty fields, prompting the user to enter the required information.

**Test data:**
User: none & pass: none


*******************************************

Test Case 5: Account Lockout after Multiple Failed Attempts

**Description:**
Confirm that the system locks the account after a specified number of consecutive failed login attempts.

**Steps to Reproduce:**

1. Navigate to the login page.
2. Enter an invalid username.
3. Enter an invalid password.
4. Repeat the above steps for the specified number of allowed attempts.

**Expected Result:**
After the specified number of failed attempts, the system should lock the account and display a message informing the user that the account has been temporarily locked for security reasons.

















