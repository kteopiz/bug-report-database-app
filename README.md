# Bug Report Database App

## Welcome to the Bug Reporting System (BRS) project!

This system is designed to help users efficiently report and manage bugs or defects in various software components. This README.md file provides essential information for developers, contributors, and users to understand, contribute, and use the Bug Reporting System.

## Getting Started

### Prerequisites

- Internet connection
- Web browser with network capabilities
- An email account

## Usage

### User Authentication

1. Open the BRS web form.
2. Log in with a valid username and password.

### Bug Submission

1. Click on the "Start New Bug Report" option.
2. Fill in the required details, including bug originator, type, and a short description.

### Bug Status and Priority

- Check the status and priority of a bug to understand its importance and progress.

### Graphical Representation

- View a graph illustrating the common trend of bugs found in each sprint for better sprint planning.

## Project Structure

**`/src`** : This directory contains all the source code files of the Bug Reporting System.

* `/src/controllers`: Contains controller files responsible for handling user requests and interacting with the model.
* `/src/models`: Contains model files defining the data structures and database interactions.
* `/src/views`: Contains view files responsible for rendering user interfaces.
* `/src/routes`: Contains route files defining the URL endpoints and their corresponding controller actions.

**`/public`** : This directory contains static assets such as images, stylesheets, and client-side JavaScript files.

* `/public/css`: Contains CSS stylesheets used for styling the user interface.
* `/public/js`: Contains client-side JavaScript files for interactive features.

**`/config`** : Contains configuration files for setting up the database connection, authentication, and other system settings.

* `/config/database.js`: Configuration file for database connection settings.
* `/config/auth.js`: Configuration file for authentication settings.

**`/views`** : Contains view templates written in HTML with embedded templating language (e.g., EJS, Handlebars) for dynamic content generation.

* `/views/layouts`: Contains layout templates used to structure the overall appearance of the application.
* `/views/partials`: Contains partial templates for reusable components (e.g., header, footer).

**`/routes`** : Contains route definitions for different URL endpoints, mapping requests to controller actions.

* `/routes/auth.js`: Route definitions related to user authentication (e.g., login, logout).
* `/routes/bugs.js`: Route definitions related to bug reporting and tracking functionalities.

**`/models`** : Contains database models defining the schema and interactions with the database.

* `/models/User.js`: Model definition for user data, including fields such as username, password, and email.
* `/models/Bug.js`: Model definition for bug data, including fields such as type, description, status, and priority.

**`/tests`** : Contains test files for unit testing and integration testing.

* `/tests/controllers`: Contains test files for testing controller actions.
* `/tests/models`: Contains test files for testing model methods.

1. **`/README.md`** : The README file provides an overview of the Bug Reporting System, including installation instructions, usage guidelines, and support information.
2. **`/package.json`** : The package.json file contains metadata about the project and dependencies required for installation.
3. **`/app.js`** : The app.js file is the entry point of the application, where the server is initialized, and middleware are configured.

We welcome contributions! Please follow the [contribution guidelines](CONTRIBUTING.md) to contribute to the Bug Reporting System.

## License

This project is licensed under the [MIT License](LICENSE).
