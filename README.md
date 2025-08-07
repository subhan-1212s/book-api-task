# Book API (Node.js + Express)

This project is a simple REST API for managing a list of books. It supports CRUD operations using Node.js and Express.js.

## 📦 Installation

```bash
npm install
```

## 🚀 Run the Server

```bash
node index.js
```

Server runs on: `http://localhost:3000`

## 📚 API Endpoints

### GET /books
Returns all books.

### POST /books
Add a new book.
- Example Body:
```json
{
  "id": 1,
  "title": "1984",
  "author": "George Orwell"
}
```

### PUT /books/:id
Update an existing book.

### DELETE /books/:id
Delete a book by ID.

## 🧪 Test
Use **Postman** or **curl** to test the API endpoints.

---

This project is part of the Web Development Internship REST API Task.
