# Admin Dashboard

> Authentication and Authorization test for Nest.js TypeScript Framework With JWT

## Installation

### 1. Clone my repo

```
  git clone https://github.com/tuankiet107/nestjs-auth.git
```

### 2. Install necessary modules

```bash
  cd nestjs-auth

  npm install
```

### 3. Run the app

```bash
# watch mode
$ npm run start:dev
```

## Test:

|                           Routes | Input(username/password) |              Result               |
| -------------------------------: | :----------------------- | :-------------------------------: |
| http://localhost:3000/auth/login | user1/user1              |      {"access_token": 'abc....'}      |
|  http://localhost:3000/protected |                          | {"userId": 1,"username": "user1"} |
