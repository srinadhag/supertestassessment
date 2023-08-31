# API Testing using SuperTest, Mocha and Chai

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
## Don't forget to give a :star: to make the project popular.

## What is it all about?

API testing in Javascript.
Being a newbie to JS, I googled for some tools and found `SuperTest`.
To introduce `SuperTest`, it is a high level abstraction of HTTP requests, making it perfect for testing APIs.

## Getting Started:

You need to have the following installed in your machine:

1. Node (Latest Version).
2. npm(Latest Version).
3. `mocha` framework is used for writing tests and `chai` for assertions, following command should help to install the required npm packages:
   `npm i -D -g supertest mocha chai mochawesome`
4. For running the tests, you need to type the command: `npm run test`. _(Check Package.json for more details)_
5. For generating the mochawesome report, run the command `npm run report` _(Check Package.json for more details.)_ It will generate and export the report in `mochawesome-report` folder from which you can open the `index.html` file to view the report.

## Talking more about the Scenarios Covered in this project:

1. Filter out list of First name and email of all the Users obtained in GET call.

2. Filter out user details by giving ID.

3. Validate response code and user details.

4. Create new user and retrieve newly created ID.

5. Validate response code and user details.

6. retrieve newly created ID.

<img src="assets/mochawesome-report.png"/>

## Below Test Cases written and Executed.


7. Update the firtname and last name using the Patch request and assert the response.

8. Validate the response code and user information.