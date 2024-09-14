# Goal Management Back-End with Node.js

## Overview
This project builds a back-end for a goal management application using Node.js, featuring technologies like **Fastify**, **Zod**, **Docker Compose**, and **Drizzle ORM**. It includes functionality for creating, tracking, and completing goals.

## Key Features
- **Database schema and seed creation**
- **Goal management**: Add, track, and complete goals
- **Pending goal tracking**

## Technologies
- **Fastify**: Web framework for high-performance routing
- **Zod**: Schema declaration and validation library
- **Docker Compose**: Container orchestration
- **Drizzle ORM**: TypeScript ORM for database operations

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/)

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/nlw-pocket-js-node-goals.git
   cd nlw-pocket-js-node-goals
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Docker containers:**
   ```bash
   docker-compose up
   ```

4. **Run database migrations and seed:**
   ```bash
   npx drizzle-kit migrate && npm run seed
   ```

5. **Start the server:**
   ```bash
   npm run dev
   ```
