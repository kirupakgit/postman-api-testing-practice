# Postman Library API Testing

This repository contains my practice collection for testing the Library API using Postman.  
It includes CRUD operations, query parameters, collection variables, scripting, and skill check tasks.

## What’s Included
- GET all books
- GET fiction books with query params
- GET book by ID
- POST: Add a new book (auto-stores ID using script)
- PATCH: Checkout a book
- DELETE: Delete a book
- Skill-check request with API key authorization and variable extraction

## Features Used
- Collection variables
- Test scripts (pm.test, pm.expect)
- API-key authentication
- JSON body validation
- Workflow automation using saved variables

## How to Use
1. Import the collection:  
   `Postman Library API v2.postman_collection.json`

2. Set environment variables (if needed):
   - `baseUrl`
   - `skillcheckBaseUrl`

3. Run the requests in order to see the workflow.

## Purpose
This project demonstrates practical API testing skills using Postman, including scripting, validations, and collection-level workflows.

