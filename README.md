# Express & PostgreSQL User API

## Setup

1. Install PostgreSQL and create a database.
2. Run the table creation SQL provided:
   ```
   CREATE TABLE users (
     id SERIAL PRIMARY KEY,
     name VARCHAR(100),
     email VARCHAR(100),
     age INTEGER
   );
   ```
3. Configure `db.js` with your database details.
4. Install dependencies:
   ```
   npm install
   ```
5. Run the server:
   ```
   node index.js
   ```

## API Endpoints

- `GET /users` - Get all users
- `GET /users/:id` - Get user by ID
- `POST /users` - Create a new user
- `PUT /users/:id` - Update user
- `DELETE /users/:id` - Delete user

Test using Postman or similar tools.
