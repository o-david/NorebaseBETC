# NorebaseBETC

## Description

NorebaseBETC is a server application built with Express.js that provides an API for managing article likes. It includes features such as rate limiting and CORS support.

## Features

- Get the like count for a specific article.
- Increment the like count for a specific article.
- Rate limiting to prevent abuse.
- CORS support for cross-origin requests.

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd NorebaseBETC
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the root directory and add your environment variables:
   ```
   PORT=3000
   MONGO_URI=<your-mongodb-connection-string>
   ```

## Usage

To start the server, run:

```bash
npm run server
```

The server will be running on `http://localhost:3000` or any port indicated in your .env.

## Live API Endpoints

- **GET** `https://norebasebetc.onrender.com/api/articles/:articleId/likes` - Get the like count for an article.
- **POST** `https://norebasebetc.onrender.com/api/articles/:articleId/likes` - Increment the like count for an article.
