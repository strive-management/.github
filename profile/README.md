# strive

Strive is a web application designed to help small businesses manage employee data, schedules, attendance tracking, and onboarding files. 

This . It contains the codebase for the backend of our application. 

## Getting Started 

Before you begin, please ensure you have node.js and npm installed. 

## Backend Installation

1. Clone the repo.
2. npm install the necessary devDependencies and dependencies.
3. Create your own .env file. and fill in your own environmental variables. 

## Usage 

Set up the server in development mode: 
```
npm run dev
```
Generate your Prisma client for managing your database. 
```
npm run prisma: generate
```
If the schema is appropriate for your project as is. 
```
npm run prisma:migrate
```
If the schema is not a fit for your project's needs please be sure to edit the schema before migrating. 

## Deployment 

When deploying to production be sure to use the following:
```
npm run build
```
```
npm run deploy
```

## Contributing 
Team Strive is not currently accepting contributions to the project. However, feel free to get in contact if you are interested in the project or have questions for our team. 
