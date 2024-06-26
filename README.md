# DryerMaster Inc Control System

This project is designed to manage and monitor IoT devices via WebSocket connections, maintain device status updates in a PostgreSQL database, provide a robust API using Express, and offer a user-friendly interface through a React application. It includes extensive logging with Winston for troubleshooting and monitoring.

## Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Architecture Overview](#architecture-overview)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This system is built to facilitate real-time communication and management of IoT devices at DryerMaster Inc. The primary goal is to ensure continuous monitoring and operational efficiency through seamless integration between the devices, server, and client applications.

## Technologies Used

- **Node.js** - Server-side JavaScript runtime environment.
- **Express.js** - Framework for building APIs.
- **React.js** - Frontend library for building user interfaces.
- **PostgreSQL** - Relational database to store device data.
- **Winston** - Logging library for Node.js.
- **WebSocket** - Technology providing full-duplex communication channels.

## Architecture Overview

### WebSocket Server

Handles real-time connections with IoT devices to monitor and control them efficiently.

### Express API

Serves as the backend API, interfacing between the PostgreSQL database and the frontend.

### React Application

Provides the user interface for real-time device data visualization and management.

### Winston Logging

Configured to log all operations, errors, and system messages for auditing and troubleshooting.

## Installation

Instructions for setting up the development environment:

```bash
# Clone the repository
git clone https://github.com/inamdryermaster/dm_server


# Install dependencies for the server
npm install
npm start
# Install dependencies for the client
cd client
npm install
npm build
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
