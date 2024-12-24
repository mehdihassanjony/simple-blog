# Blog Website With TypeScript, NestJS, PostgreSQL, TypeORM, React, and SwaggerJS

This is a blog post website application built using NestJS for the backend, React for the frontend, and various technologies to handle different aspects of the application. The stack includes:

- **TypeScript**: For type checking in JavaScript.
- **NestJS**: A Node.js framework built on top of Express, providing a structured and scalable solution for server-side applications.
- **PostgreSQL**: The relational database management system used to store blog posts, comments, likes, and user data.
- **TypeORM**: The Object-Relational Mapping (ORM) used to connect and interact with the PostgreSQL database.
- **SwaggerJS**: Used for API documentation and testing.

## Role-Based Permissions

Users have different roles that dictate the actions they can perform on posts:

- **Admin**: Can create, update, and delete posts, as well as manage all comments and likes.
- **Author**: Can create and update their own posts, comment on others' posts, and like posts.
- **Reader**: Can only view posts and like them, without the ability to comment or create content.

## Database Design

- [Database Design For The Blog](https://drawsql.app/teams/own-132/diagrams/blog/embed)

## Getting Started

### Clone the repository

```bash
$ git clone git@github.com:mehdihassanjony/simple-blog.git
$ cd server
```

### Create a `.env` file and put in the right credentials

```bash
$ cp .env.sample .env
```

## Installation

Install the required dependencies:

```bash
$ npm install
```

### API Documentation

- Access the API documentation at [http://localhost:3000/api#/](http://localhost:3000/api#/)

---

Let me know if you need more changes or specific instructions on role-based handling in the backend or frontend!
