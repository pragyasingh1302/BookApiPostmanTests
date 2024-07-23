# Bookstore API Testing

## Project Description
This project contains Postman tests for a bookstore web application's API. The tests cover adding, retrieving, updating, and deleting books.

## Instructions to Run the Tests

1. **Prerequisites:**
   - Ensure you have Postman installed on your machine.

2. **Import Postman Collection:**
   - Download the `BookStoreAPITests.postman_collection.json` file from this repository.
   - Open Postman.
   - Click on `File -> Import`.
   - Select the `BookStoreAPITests.postman_collection.json` file and import it.

3. **Set Up Environment Variable:**
   - Go to the `Environments` tab in Postman.
   - Click on `Add` to create a new environment.
   - Name the environment (e.g., "Bookstore API Environment").
   - Add a new variable named `BaseURL`.
   - Set the initial value and current value of `BaseURL` to the base URL of your API (e.g., `http://yourapiurl.com`).
   - Save the environment.

4. **Run the Collection:**
   - Go to the `Collections` tab in Postman.
   - Select the imported "Bookstore API Tests" collection.
   - Click on `Run` to open the Collection Runner.
   - Select the environment you just created from the dropdown.
   - Click `Start Test` to run the tests in sequence.

## Dependencies and Prerequisites
- Postman

## Feedback Points
- Any improvements in the test cases or structure.
- Edge cases that might be missing.
- Suggestions for better test coverage.

## Contact Information
- Pragya Singh
- work.pragyasingh@gmail.com
