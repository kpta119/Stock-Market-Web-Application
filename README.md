# Stock Market Web Application

## Overview

This project is a web application designed to manage user portfolios, transactions, and assets. The application provides various endpoints for user authentication, portfolio management, and asset transactions. The backend is built using Node.js and Express, and it connects to a MySQL database using Sequelize ORM.

## Project Structure

The project is organized into the following main directories:

- **backend**: Contains the server-side code, including routes, models, and middleware.
  - **routes**: Defines the API endpoints for user authentication, portfolio management, and asset transactions.
  - **models**: Defines the Sequelize models for interacting with the MySQL database.
  - **middleware**: Contains middleware functions for authentication and other purposes.
  - **tests**: Contains unit and integration tests for the backend endpoints.
  - **config**: Contains configuration files for the database and other settings.

- **frontend**: Contains the client-side code, including React components and assets.
  - **public**: Contains static assets and the main HTML file.
  - **src**: Contains the React components, styles, and other client-side code.

## Database

The project uses MySQL as the database, and Sequelize ORM is used to interact with the database. The database models are defined in the `backend/db/models` directory.

## Responsibilities

I was responsible for developing the backend of the application, including:

- Designing and implementing the API endpoints.
- Creating the database models and setting up the MySQL database.
- Writing unit and integration tests for the backend endpoints.
- Ensuring secure authentication and authorization using JWT and middleware.
