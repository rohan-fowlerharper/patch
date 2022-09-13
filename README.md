# Patch

TODO: install husky
TODO: add github actions for linting, testing and prettier
TODO: add github issues page w/ tickets

Welcome to Patch (pat or scratch), an interactive web application that is geared towards pet lovers 

# Getting Started

This repository uses [TailwindCSS](https://tailwindcss.com/) for styling. For the best developer experience, install the [TailwindCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss) extension for VSCode.

## Frontend:

- [React](https://beta.reactjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [React Router](https://reactrouter.com/)
- [Vite](https://vitejs.dev/)

## Backend:

- [Express](https://expressjs.com/)
- [Knex](http://knexjs.org/)
- [PostgreSQL](https://www.postgresql.org/) # for deployment
- [SQLite3](https://www.sqlite.org/index.html) # for development

# Testing

- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Vitest](https://vitest.dev/)
- [nock](https://github.com/nock/nock)
- [supertest](https://github.com/visionmedia/supertest)


# Contributing Guide

To run this project:

```sh
# clone to your local machine
cd patch
npm install
npm run db:reset # will run migrations and seeds
npm run dev
```

To preview what a production build would look like:
```sh
npm run preview

## or
npm run build
NODE_ENV=staging npm start
```
**NOTE**: Only do this when you want to view the staging build, use `npm run dev` for development.
