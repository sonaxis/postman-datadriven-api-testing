# postman-datadriven-api-testing
# Data-Driven API Testing using Postman

## Project Overview
This project demonstrates data-driven REST API testing using Postman on the ReqRes public API. 
It validates an end-to-end user lifecycle including authentication, user creation, update, and deletion using dynamic data handling and automated response validations.

## APIs Covered
- Login (Token generation)
- Create User
- Update User
- Delete User

## Key Features
- Data-driven testing using CSV files
- Token-based authentication handling
- Environment and variable management
- Request chaining across multiple APIs
- Automated response validation using Postman test scripts
- End-to-end API workflow execution using Collection Runner

## Tools & Technologies
- Postman

## How to Run the Project
1. Import the Postman collection from the `collections` folder
2. Import the environment file from the `environments` folder
3. Select the environment in Postman
4. Open Collection Runner
5. Load the CSV file from the `data` folder
6. Execute the collection

## Validations Implemented
- HTTP status code validation
- Token presence validation
- Dynamic user ID capture
- Successful update and deletion verification

## Notes
- This project uses the ReqRes public API for demonstration purposes
- No sensitive information is included
- Created for learning and portfolio showcasing


