# Madrigal
## Knowledge, Blogging and Bookmarking Toolkit

## Introduction

Madrigal is a platform designed to help manage personal knowledge base, bookmark databases and blog manager. The platform is built using Typescript, Node and React, and follows functional programming principles. The database is built using Postgres, and follows SOLID principles.

## Features

Madrigal comes with the following features:

- Personal Knowledge Base manager to help you manage and track knowledge on different topics.
- Bookmark Database to help you keep track of important web links.
- Blog Manager to help you write and manage your blog posts.
- User authentication and authorization to ensure only authenticated users can access the platform.
- Responsive user interface for easy navigation and interaction.
- SOLID principles to ensure that the code is maintainable, testable, and scalable.

## Technical Specifications

Madrigal is built using the following technologies and libraries:

- Typescript: for type safety and improved developer experience.
- Node: for server-side logic and interacting with the database.
- React: for building the user interface.
- Postgres: for data storage and retrieval.
- Express: for building the RESTful API.
- JWT: for user authentication and authorization.
- Sequelize: for interacting with the Postgres database.

## Database Schema

Madrigal uses a Postgres database to store data. The database schema is designed to follow SOLID principles and ensure data consistency and integrity. The following tables are used in the database:

### Users

- id: UUID, primary key
- email: string, unique
- password: string

### Notes

- id: UUID, primary key
- title: string
- description: string
- created_by: UUID, foreign key to Users table

### Bookmarks

- id: UUID, primary key
- title: string
- url: string
- created_by: UUID, foreign key to Users table

### Posts

- id: UUID, primary key
- title: string
- content: string
- created_by: UUID, foreign key to Users table

## Conclusion

Madrigal is a powerful platform that helps you manage your personal knowledge base, bookmark databases, and blog manager. It is built using Typescript, Node, and React, and follows functional programming principles. The Postgres database schema follows SOLID principles to ensure data consistency and integrity. Madrigal is easy to use, secure, and scalable.