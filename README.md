# Postman API Project (API ReqRes)

This is a project from the BootCamp, "The Complete Software Testing Bootcamp", organized by Nezam Academy.

ReqRes is a hosted REST API that is ready to respond to AJAX requests. It allows testers to test APIs for free.  
Below are details about the API Endpoints and how you can use them.

### URL Base
The URL base for API ReqRes is: https://reqres.in/

#### API testing tool
This project was done using Postman. The provided Postman collection (JSON format) is available in this repository and can be imported into Postman to test the API endpoints quickly.

### Tested Endpoints

###### 1. List users
Method: GET

Description: Verify that the users are listed successfully

Test Cases: "Users are listed successfully", "Response time is less than 1000ms", "Verify page data"

###### 2. List a single user
Method: GET

Description: Verify that a single user is listed successfully

Test Cases: "Single user is listed successfully", "Response time is less than 1000ms", "Correct user ID"

###### 3. List a not-found user
Method: GET

Description: Verify that a single user is not found

Test Cases: "User not found", "Response time is less than 1000ms"

###### 4. List resources
Method: GET

Description: Verify that the resources are listed successfully

Test Cases: "Resources are listed successfully", "Response time is less than 1000ms", "Verify page data"

###### 5. List single resource
Method: GET

Description: Verify that a single resource is listed successfully

Test Cases: "Single resource listed successfully", "Response time is less than 1000ms", "Correct resource ID"

###### 6. List a not-found resource
Method: GET

Description: Verify that a single resource is not found

Test Cases: "Resource not found", "Response time is less than 1000ms"

###### 7. Create user
Method: POST

Description: Create a new user

Test Cases: "User created successfully", "Response time is less than 1000ms"

###### 8. Update user 1
Method: PUT

Description: Update a user successfully

Test Cases: "User is updated successfully", "Response time is less than 1000ms"

###### 9. Update user 2
Method: PATCH

Description: Update a user successfully

Test Cases: "User updated successfully", "Response time is less than 1000ms"

###### 10. Delete user
Method: DELETE

Description: Delete user successfully

Test Cases: "User is deleted successfully", "Response time is less than 1000ms"

###### 11. Register successful
Method: POST

Description: Registration is successful

Test Cases: "Registration is successful", "Response time is less than 1000ms"

###### 12. Register unsuccessful
Method: POST

Description: Registration is unsuccessful

Test Cases: "Registration is unsuccessful", "Response time is less than 1000ms"

###### 13. Login successful
Method: POST

Description: Login is successful

Test Cases: "Login is successful", "Response time is less than 1000ms"

###### 14. Login unsuccessful
Method: POST

Description: Login is unsuccessful

Test Cases: "Login is unsuccessful", "Response time is less than 1000ms"

### Link to ReqRes API documentation
https://reqres.in/
