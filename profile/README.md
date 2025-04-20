# Phantom Chat

Phantom is a modern, real-time messaging application built with a focus on performance, scalability, and developer experience.

## Features

- **Real-time Messaging**: Built with WebSocket support for instant message delivery.
- **Authentication**: Secure JWT-based authentication with token refresh and cleanup.
- **Database**: Uses PostgreSQL with Drizzle ORM for type-safe database interactions.
- **Logging**: Custom logging system with timestamps and caller information.
- **Performance Monitoring**: Built-in performance monitoring for API requests.
- **Cron Jobs**: Scheduled tasks for token cleanup and other maintenance.

## Tech Stack

- **Framework**: [Elysia](https://elysiajs.com/) - A fast, type-safe, and expressive web framework for Bun.
- **Runtime**: [Bun](https://bun.sh/) - A modern JavaScript runtime designed for speed and simplicity.
- **Database**: [PostgreSQL](https://www.postgresql.org/) - A powerful, open-source relational database.
- **ORM**: [Drizzle ORM](https://orm.drizzle.team/) - A type-safe SQL query builder and ORM.
- **Authentication**: [JSON Web Tokens (JWT)](https://jwt.io/) - Secure token-based authentication.
- **WebSocket**: Built-in WebSocket support for real-time communication.
- **Logging**: Custom logging system with timestamps and caller information.
