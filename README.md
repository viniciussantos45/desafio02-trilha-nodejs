# desafio02-trilha-nodejs

A **Todos API with user plans** built as the second challenge for the [Rocketseat Ignite](https://www.rocketseat.com.br/ignite) Node.js bootcamp, focusing on middleware design.

## Objective

The objective of this challenge is to build a todo management API with a user account system and plan restrictions — free users can have up to 10 todos, while pro users have unlimited todos — enforced through a chain of Express middlewares.

## Features

- Create user accounts (free and pro plans)
- Create, list, update, mark as done, and delete todos
- Middleware chain: account existence check, plan availability check, todo existence check, user ID lookup
- Comprehensive test coverage for middlewares and routes

## Tech Stack

- Node.js
- Express
- Jest

## Getting Started

```bash
yarn install
yarn dev

# Run tests
yarn test
```
