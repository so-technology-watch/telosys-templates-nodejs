# Node.JS Telosys 3 Template

This is a Telosys Template for code generation.
It's purpose is to generate a NodeJS REST API after having provided a DSL model.

The generated server Application is A NodeJS REST API using SQLite as a database (sqlite.db). The code is written in ES6 and uses Promises.

## Installation

1. Download the template.
2. Provide your DSL model.
3. Generate the code with Telosys.  
4. Navigate to the generated code's root folder.
5. Open the generated TEMPLATE_package.json file adapt it to your project then rename it to package.json.
6. Install the dependencies with the following command : `npm install`

## Requirements

- [NodeJS](https://nodejs.org/en/) to run the application.
- [Npm](https://www.npmjs.com/) to install dependencies (see the full list below at "Dependencies").
- [Postman](https://www.getpostman.com/) to test the API.

## Getting started

1. Install this application (See Installation).
2. Start the server with : `node index.js`
3. Connect Postman to the API at : `http://localhost:3000`
4. Try the different entities routes of the API based on your DSL model.

## Dependencies (installed via `npm install`)

- [Body-parser](https://www.npmjs.com/package/body-parser), a Node.js body parsing middleware.
- [Ejs](https://www.npmjs.com/package/ejs) embedded JavaScript templates.
- [Express](https://www.npmjs.com/package/express), a fast and minimalist web framework for node.
- [Sqlite](https://www.npmjs.com/package/sqlite), a wrapper library that adds ES6 promises and SQL-based migrations API to [sqlite3](https://www.npmjs.com/package/sqlite3)*.
- [Bluebird](https://www.npmjs.com/package/bluebird) promise library.

*Sqlite3 : (Asynchronous, non-blocking SQLite3 bindings for Node.js.)

## Credits

- Made by [Romuald Tuffreau](https://github.com/romwaldtff).

## Thanks

- [Laurent Guerin](https://github.com/l-gu), creator of [Telosys Tools](http://www.telosys.org/).

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html) (See the LICENSE file in this repository).
