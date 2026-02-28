# Centro de Acogida (DWES) — Express + EJS Routes

## Author
Manuel Aparicio

## Overview
This project was developed for the **DWES (Server-side Web Development)** module.  
It is a **Node.js + Express** application that demonstrates:
- basic routing
- server-side rendering with **EJS**
- route parameters
- JSON responses (API-style endpoint)

## Tech Stack
- Node.js
- Express
- EJS

## Requirements
- Node.js 18+ recommended

## Installation
`npm install`

## Run the project
`node app.js`
The server will start (typically on http://localhost:3000 unless configured differently).

## Main Endpoints
- GET `/bienvenida`
Renders an EJS page with dynamic content (e.g., a name).
- GET `/edad-perruna/:edadHumana`
Uses a route parameter to calculate and return the dog's age equivalent.
* Example:
`/edad-perruna/10`
- GET `/numeros-impares`
Returns a JSON response with odd numbers.

## Project Notes
Recommended `.gitignore`:
```txt
node_modules
.env
