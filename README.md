# Automated tests

Authomated tests for BPDTS- API Tests. Currently compatible with Postman/Newman.


## Technical documentation

This is a NodeJS application which calls automated scripts written for Postman/Newman.

Current tests are:

**User** Runs the "happy path" to get a list of users, search user by id and search users by city. Have covered one unhappy path invalid user id return 404

Each request checks if the data returned by the API is valid, and ensures that each valid operation can be successfully called for each endpoint.


### Running the application
Clone the repo -
Import the folder in postman IDE
Run the collection - you can run with userTestData.csv or userList.json file attached for data driven testing.

## Licence

[MIT License](https://opensource.org/licenses/MIT)
