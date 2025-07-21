# Solace Full‑Stack Task

This repository is a sample full‑stack application demonstrating:

- **Backend:** NestJS + GraphQL serving static JSON
- **Frontend:** React + TypeScript + MUI + react‑hook‑form + graphql‑request

## Project Structure

solace-fullstack-task/
├── backend/ # NestJS GraphQL server
│ ├── src/
│ ├── tsconfig.json
│ └── package.json
└── frontend/ # React + MUI client
├── src/
├── tsconfig.json
└── package.json

## Requirements

- Node.js ≥ 16
- npm

## Setup & Run

### 1-Backend

```bash
cd backend
npm install
npm run start:dev      # runs on http://localhost:3000/graphql

GraphQL Playground available at:
http://localhost:3000/graphql


2-Frontend

In a separate terminal:

cd frontend
npm install
npm start

App runs at:
http://localhost:3001

3-Features
Department Card View

Displays department details fetched via GraphQL.

Edit Department

Opens a dialog with prefilled fields.

Saves changes via updateDepartment mutation.

View Employee Details

Opens a dialog showing full employee info.

Delete Employee

Shows a confirmation dialog.

Removes employee via deleteEmployee mutation.

Responsive & Pixel‑Perfect

Layout adapts to screen sizes.

Matches the provided Figma design.


4-Architecture & Performance
NestJS + GraphQL for a type‑safe API.

React + TypeScript + MUI for a modern, maintainable frontend.

React Hook Form for performant, scalable forms.

graphql-request for lightweight GraphQL client.

CSS Grid / MUI Box for responsive layouts.


5-Next Steps
Add unit and integration tests.

Integrate a real database (e.g. PostgreSQL).

Implement authentication & authorization.

Add error‑handling UI (toasts/snackbars).

Introduce pagination or lazy‑loading for large employee lists.



License
This project is provided for technical evaluation only.
No license. All rights reserved by Solace.


```
