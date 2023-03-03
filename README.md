# Build-And-Verify-Your-Code-with-Harrison.Ai
Write input validation and unit &amp; integration tests for React application

Here is the background information on your task
In this task, the team will create input validation logic along with its unit test.

Input validation is one of the most common functionalities in the software engineering world. Inevitably, we use input validation everywhere, from username and password, postal address, person name, and many other inputs.

Despite its commonalities, input validation is also one of the most error-prone code sections due to its complex nature of containing a lot of logic.

One of the way to make complex-logic code section like this input validation more robust is by using unit test. With unit test, we will have more confidence in shipping the code to production if all tests have passed. This unit test also serves as documentation for the whole team. One could simply read the unit test code to get a grasp of what the real code is actually doing.

The input validation logic created on this task will validate email address to be in the correct email address format, also validating the password to follow some given rules. It will show success message when validation passed and error message when there is something wrong in email and/or password inputted by user.

For simplicity, we only need to check if the email and password are in the correct form. We don’t need to submit the input to server or check if the inputted email and password are matching with the database


Here is your task:
Write input validation for email and password form.

For email, you can simply use this library for validation https://www.npmjs.com/package/email-validator
For password, please follow these requirements:

Minimum of 8 characters
Should contains both uppercase and lowercase letter
Minimum of 1 numerical digit (0-9)
Minimum of 1 special character (!@#$%^&*, etc)
Show success message when validation passed and error message when validation failed.

For the success message, you can use existing success snackbar that is already shown in the template project every time we click the submit button (still has no logic).

For the error message, you can use error state from text-fields Material UI component https://mui.com/components/text-fields/#validation

Validation logic needs to be unit tested. You can use jest for unit testing https://jestjs.io/
