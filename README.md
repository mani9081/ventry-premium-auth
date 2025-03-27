1. Frontend (Next.js/React with TypeScript)
First, create a new Next.js project:

npx create-next-app@latest ventry-auth --typescript
cd ventry-auth

2. Backend (Node.js/Express)
 Create a new folder for the backend:

mkdir server
cd server
npm init -y
npm install express bcryptjs jsonwebtoken dotenv cors sqlite3


3. Database Setup (SQLite)
The code  automatically creates the SQLite database file when you start the server. For production, you would want to use PostgreSQL instead.

4. Environment Variables
Create a .env file in your server directory:

JWT_SECRET=your_very_secure_secret_key_here
PORT=5000


5. Running the Application
Start the backend:

cd server
node app.js

Start the frontend (in another terminal):

cd ventry-auth
npm run dev
