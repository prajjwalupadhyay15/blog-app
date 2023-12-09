# BlogsUp

## Overview

This is a simple blog web application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to create, read, update, and delete blog posts.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Database Seeding](#database-seeding)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [Owner](#Owner)

## Features

- User authentication (sign up, log in, log out)
- CRUD operations for blog posts
- Responsive design for various screen sizes
- MongoDB for data storage
- Express.js for server-side development
- React.js for the frontend
- Node.js for server runtime

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB installed and running
- Git installed

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/its-nikkk/BlogsUp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd BlogsUp
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Configuration

1. Create a `.env` file in the root of the project:

   ```plaintext
   MONGODB_URI=your-mongodb-uri
   SECRET_KEY=your-secret-key
   ```

   Replace `your-mongodb-uri` with your MongoDB connection string and `your-secret-key` with a secret key for JWT token generation.

## Database Seeding

To seed the database with sample data, run the following command:

```bash
npm run seed
```

This will populate your MongoDB database with initial data for testing purposes.

## Usage

1. Start the development server:

   ```bash
   npm run dev
   ```

   This will start both the backend and frontend servers concurrently.

2. Access the application in your browser at [http://localhost:3000](http://localhost:3000).

## Folder Structure

```
- /client      # React.js frontend
- /server      # Node.js and Express.js backend
- /models      # MongoDB models
- /routes      # Express.js routes
- /config      # Configuration files
- /public      # Public assets
- /views       # Server-rendered views (if applicable)
- /utils       # Utility functions
```

## Contributing

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## Owner
@its-nikkk and @prajjwalupadhyay15
