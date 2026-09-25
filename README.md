# Expense Tracker

A Node.js-based Expense Tracker project designed to provide a foundation for managing personal expense-related functionality with authentication and secure password handling.

## Overview

The **Expense Tracker** project uses Node.js and includes authentication-related dependencies for password hashing and JSON Web Token (JWT) based authentication.

The project currently includes:

* Password hashing with **bcryptjs**
* JWT-based authentication with **jsonwebtoken**
* Environment-variable support through `.env`
* Build output and dependency files excluded from version control

## Tech Stack

| Technology     | Purpose                       |
| -------------- | ----------------------------- |
| Node.js        | JavaScript runtime            |
| bcryptjs       | Password hashing              |
| JSON Web Token | Authentication/token handling |
| npm            | Package management            |

The project declares `bcryptjs` version `3.0.3` and `jsonwebtoken` version `9.0.3`.

## Dependencies

### bcryptjs

Used for password hashing and secure password handling.

### jsonwebtoken

Used for creating and handling JSON Web Tokens for authentication.

## Project Structure

The complete source structure was not included in the provided files, so the exact folder structure is not documented here.

A typical project may contain directories such as:

```text
expense-tracker/
├── src/
├── .env
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
```

> The exact structure should be updated according to the actual project folders.

## Environment Variables

Environment files are intentionally excluded from Git. The project's `.gitignore` excludes `.env` and `.env.*` while allowing `.env.example`.

If the project requires environment variables, create a local `.env` file based on `.env.example`.

**Never commit real secrets or credentials to GitHub.**

## Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd expense-tracker
```

Install dependencies:

```bash
npm install
```

The project's lock file records the required npm dependencies and their versions.

## Running the Project

The available `package.json` data does not include scripts such as `start`, `dev`, or `build`, so the exact run command cannot be documented from the provided files alone.

Check the project's `package.json` for the available scripts and run the appropriate command.

For example, if a start script exists:

```bash
npm start
```

## Security

This project uses:

* **bcryptjs** for password hashing
* **jsonwebtoken** for JWT-based authentication

Keep authentication secrets and other sensitive configuration values inside environment variables rather than committing them to the repository.

## Git & GitHub

The repository is configured to ignore common generated and sensitive files, including:

```text
node_modules/
.env
.env.*
dist/
build/
coverage/
*.log
.vscode/
.idea/
.DS_Store
Thumbs.db
```

This helps prevent dependencies, secrets, build artifacts, logs, and editor-specific files from being committed accidentally.

## Status

🚧 **Project under development**

More project-specific documentation can be added as additional source files and functionality are documented.

## Author

**Kuldeep Singh**

B.Tech CSE
Bikaner Technical University
