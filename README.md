# Moovsmart - End-to-End API Testing Portfolio

Complete REST API testing project for a real estate platform using **Postman** and **SoapUI**.

## Project Overview
This portfolio project demonstrates end-to-end API testing for Moovsmart, covering key business flows from user registration to property management and messaging.

## Tested Features
- User registration with dynamic email generation and validation
- Login flow with Basic Auth and access token extraction
- Property CRUD operations (Create, Read, Update, Delete)
- Messaging system (send new message + list incoming/outgoing)
- Property search and showcase endpoints (for sale / for rent)
- Negative testing and error handling (weak password, duplicate email, missing fields, etc.)

## Technologies & Techniques Used
- **Postman**: Collections, Environment Variables, Pre-request Scripts, JavaScript Test Scripts
- **SoapUI**: REST API testing with assertions
- Dynamic test data generation
- Request chaining between tests
- Status code, response time, JSON schema and data validation

## Repository Contents
- `postman/` → Postman Collection + Environment files
- `soapui/` → SoapUI project file
- `documentation/` → API endpoints documentation
- `screenshots/` → Test execution evidence

## How to Run
1. Import the Postman collection and environment
2. Update the `backendURL` variable to your local server
3. Run the collection using Collection Runner or Newman

## Skills Demonstrated
- Designing complete API test suites
- Working with authentication (Basic Auth + token)
- Creating reusable and maintainable test collections
- Handling positive, negative and edge cases

---

**Technologies:** Postman, SoapUI, REST API, JavaScript
