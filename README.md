# E-Commerce Backend (Module 13 Challenge)

[![License Badge](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A working backend for an example e-commerce database

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Questions and Contact](#questions-and-contact)

## Installation

1. Clone the repository to your local machine.

   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```

2. Install the project's dependencies by running:

   ```bash
   npm install
   ```

3. Make sure you have mySQL installed on your machine, login to mySQL CLI, and create the database

   ```bash
   mysql -u 'username' -p
   ```

   ```mysql
   source db/schema.sql
   quit
   ```

4. Seed the database
   ```bash
   node seeds/index.js
   ```

## Usage

This is an example backend for an E-Commerce website. You can use Insomnia to test the endpoints found in the routes folder of the project.

1. Run the server with node using

   ```bash
   node server.js
   ```

2. Use insomnia or your application of choice to test the endpoints and manipulate the database.

## Credits

N/A

## License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

You can find the full license text in the [LICENSE](LICENSE) file.

## Questions and Contact

Thank you for checking out the project!

If you have any questions or need further assistance with this project, feel free to reach out. You can contact me through the following methods:

- **GitHub Issues**: Please use the Github Issue Tracker for bug reports, feature requests, or general questions related to the project. You can find my Github profile @[nephh](https://github.com/nephh)