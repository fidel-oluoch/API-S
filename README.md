# User Management API

## Setup
1. Clone the repository
2. Run `npm install`
3. Start the server: `node index.js`
4. API will be available at `http://localhost:3000`

## API Endpoints

### Get User by ID
- **URL**: `/api/users/:id`
- **Method**: `GET`
- **URL Params**: `id=[integer]`
- **Success Response**: 
  - Code: 200
  - Content: `{ id: 1, name: "fidel", email: "foluoch52@gmail.com" }`
- **Error Response**:
  - Code: 404
  - Content: `{ message: "User not found" }
