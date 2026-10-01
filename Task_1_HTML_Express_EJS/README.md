# Task 1 – HTML Structure and Basic Server Interaction

## Cognifyz Full Stack Development Internship

### Objective

To understand HTML form creation, basic server interaction, Express.js routing, form submission, and server-side rendering using EJS.

## Technologies Used

- HTML5
- CSS3
- Node.js
- Express.js
- EJS

## Project Description

This project is a simple Student Registration System developed as part of the Cognifyz Full Stack Development Internship.

The application allows users to enter student details through an HTML form. The submitted data is sent to an Express.js server using a POST request. The server processes the submitted information and uses EJS to dynamically generate a result page.

## Features

- Student registration form
- Form validation using HTML
- Express.js server
- POST request handling
- Server-side rendering using EJS
- Dynamic result page
- Basic responsive styling

## Project Structure

```text
Task-01-HTML-Express-EJS/
│
├── app.js
├── package.json
├── package-lock.json
├── .gitignore
│
├── views/
│   ├── index.ejs
│   └── result.ejs
│
└── public/
    └── style.css