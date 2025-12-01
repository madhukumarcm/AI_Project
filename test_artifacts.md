**Test Plan**
Objective: 
The main objective of this test plan is to validate the implemented login functionality, ensure correct users get redirected to the dashboard and incorrect inputs generate an error message.

Scope:
This test plan will cover:

1. Validation of the presence of login elements (email and password fields, login button).
2. Login with valid credentials and redirection to the dashboard.
3. Login with incorrect credentials, ensure error message is displayed.
4. Validation of scenario where either or both fields are left empty.

Responsibilities:
The test team will be responsible for: planning, designing, executing the tests, and reporting bugs. The development team will be responsible for fixing the bugs.

**User Scenarios**

1. **Scenario 1**: User enters correct credentials
    1. Launch application
    2. Navigate to login page
    3. Input valid email and password
    4. Click login
    5. Verify, if redirected to the dashboard

2. **Scenario 2**: User enters incorrect credentials
    1. Launch application
    2. Navigate to login page
    3. Input invalid email and/or password
    4. Click login
    5. Verify, if an error message is displayed

3. **Scenario 3**: User leaves a field or both fields empty
    1. Launch application
    2. Navigate to login page
    3. Leave the email and/or password field empty
    4. Click login
    5. Verify, if an error message is displayed

**Test Data**

*Valid Data*:

Email: testuser@gmail.com
Password: password123

*Invalid Data*: 

Email: invalidemail@gmail.com
Password: wrongpassword

*Empty field data*:

Email: [blank]
Password: password123

Email: testuser@gmail.com
Password: [blank]

Email: [blank]
Password: [blank]