# Notes App Back-End

A back-end API for a notes application built with Node.js and Hapi.js. This API handles CRUD operations for notes, providing endpoints for creating, reading, updating, and deleting notes.

## Features

- **Create**: Add new notes to the system.
- **Read**: Retrieve existing notes.
- **Update**: Modify existing notes.
- **Delete**: Remove notes from the system.

## Installation

### Prerequisites

- Node.js >= 14.x
- npm (Node Package Manager)

### Steps

1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/notes-app-back-end.git
    cd notes-app-back-end

   
2. **Install Dependencies**
    ```bash
    npm install
   
3. **Set Up Environment Variables**
    Create a .env file in the root directory and configure the necessary environment variables. Example:
    ```plaintext
    PORT=3000

4. Start the Server with Nodemon
   For development, use nodemon to automatically restart the server on code changes:
   ```bash
   npm run dev

5. **For production, start the server with:**
    ```bash
    npm start
The server will be running on http://localhost:3000.

## API Endpoints
- POST /notes: Create a new note.
- GET /notes: Retrieve all notes.
- GET /notes/{id}: Retrieve a specific note by ID.
- PUT /notes/{id}: Update a specific note by ID.
- DELETE /notes/{id}: Delete a specific note by ID.

## License
This project is licensed under the MIT License.

## Acknowledgements
- Node.js
- Hapi.js
- Nodemon (for automatic server restarts during development)
