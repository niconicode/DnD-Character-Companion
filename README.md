# DND Real-Time Character Sheet Web App

CS410 Long Project
Fall 2024

This app will allow players and DMs to log in create and store character sheets, as well as update them in real time. The DM will also have the ability to update any character sheet in real time. 

Built with Node.js, Express, MongoDB, Socket.io, and JWT for authentication.

## Features
- **User Authentication**
  - Secure login/signup system
  - JWT-based session management
  - Password encryption using bcrypt

- **Character Management**
  - Create new character sheets
  - Real-time updates across all connected clients
  - Automatic ability modifier calculations
  - Equipment management system
  - Character stats tracking (HP, AC, etc.)

- **DM Tools**
  - Overview of all player characters
  - Real-time character sheet modifications
  - Character status monitoring

## Technology Stack
- **Frontend**
  - HTML5/CSS3
  - JavaScript
  - Socket.IO Client
  - Bootstrap

- **Backend**
  - Node.js
  - Express.js
  - MongoDB
  - Socket.IO
  - JWT Authentication

## Prerequisites

* Node.js (v18 or higher)
* Express
* MongoDB
* Socket.io
* JWT for authentication

## Installation

1. Clone the repository: 
HTTP: `git clone https://github.com/CS410-DND-CHARACTER-COMPANION/cs410project.git`
SSH: `git clone git@github.com:CS410-DND-CHARACTER-COMPANION/cs410project.git`

2. Install dependencies: `npm install`

3. Start the server: `node renderServer/backend/server.js`

4. Access the app in your browser at `http://localhost:3000`
