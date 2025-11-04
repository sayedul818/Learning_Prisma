# Learning Prisma Project

This repository contains a learning project for Prisma, a next-generation ORM for Node.js and TypeScript.

## Description

This project serves as a hands-on learning resource for working with Prisma, demonstrating database operations, schema management, and best practices for building applications with Prisma ORM.

## Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- A supported database (PostgreSQL, MySQL, SQLite, or SQL Server)

## Setup

1. Clone the repository:
```bash
git clone https://github.com/sayedul818/Learning_Prisma.git
cd Learning_prisma
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up your database connection:
   - Create a `.env` file in the root directory
   - Add your database connection string:
     ```
     DATABASE_URL="your-database-connection-string"
     ```

4. Run Prisma migrations:
```bash
npx prisma migrate dev
```

## Features

- Database schema management with Prisma Schema
- CRUD operations using Prisma Client
- Database migrations
- Type-safe database queries
- Relation management

## Available Scripts

- `npx prisma studio` - Open Prisma Studio to view and edit your data
- `npx prisma migrate dev` - Run migrations in development
- `npx prisma generate` - Generate Prisma Client

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
