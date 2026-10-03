# FerryWala

AI-powered hyperlocal street vendor marketplace built with React, Spring Boot, MySQL, JWT authentication and realtime tracking.

> Items in **[brackets]** are placeholders. Replace each with what the code actually does, or delete the line. Nothing here should describe behaviour the project does not have.

## Overview

FerryWala is a marketplace for hyperlocal street vendors. The frontend is a React app, the backend is a Spring Boot service, data lives in MySQL, access is protected with JWT authentication, and realtime tracking is part of the platform.

## Problem

**[One or two sentences: what problem do street vendors or their customers face that this project addresses?]**

## Solution

FerryWala brings vendors onto a single marketplace with authenticated access and realtime tracking. **[Add one sentence on how a vendor and a customer actually use it.]**

## Features

Confirmed by the repository description:

- Hyperlocal street vendor marketplace
- JWT authentication
- Realtime tracking
- **[AI-powered: describe the AI component, or remove "AI-powered" if it is not implemented yet]**

**[Add each further feature only once it exists in the code, for example vendor listing, ordering, search.]**

## Tech stack

| Layer | Technology |
| --- | --- |
| Frontend | React, JavaScript |
| Backend | Spring Boot (Java) |
| Database | MySQL |
| Auth | JWT |
| Realtime | WebSockets **[confirm]** |

## Architecture

```mermaid
flowchart LR
  UI[React frontend] -->|REST + JWT| API[Spring Boot backend]
  API --> DB[(MySQL)]
  UI <-->|WebSockets [confirm]| API
```

**[Adjust the diagram to match the real data flow, for example if tracking uses a different channel.]**

## Project structure

```text
FerryWala/
├── frontend/   # React application
└── backend/    # Spring Boot application
```

## Setup

**Prerequisites:** JDK **[version]**, Node.js **[version]**, MySQL **[version]**.

1. Clone the repository
   ```bash
   git clone https://github.com/manishyadav73/FerryWala.git
   cd FerryWala
   ```
2. Create a MySQL database and set its connection details in the backend's Spring Boot configuration file **[path]**.
3. Start the backend from `backend/` **[command: Maven or Gradle wrapper, confirm which the project uses]**.
4. Start the frontend from `frontend/` **[commands, for example install and start scripts from package.json]**.
5. Open the app at **[local URL and port]**.

Never commit real database passwords or JWT secrets. Use environment variables or an ignored config file.

## Screenshots

**[Add 2–4 screenshots to a `docs/screenshots/` folder and reference them here.]**

## Future improvements

**[List only planned work you genuinely intend to do.]**

## Author

Manish Kumar · [@manishyadav73](https://github.com/manishyadav73)
