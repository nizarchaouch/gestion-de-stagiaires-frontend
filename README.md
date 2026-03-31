# Internship Management Frontend

![Vue.js](https://img.shields.io/badge/Vue.js-Frontend-42b883)
![Vue Router](https://img.shields.io/badge/Vue%20Router-Navigation-4FC08D)
![Pinia](https://img.shields.io/badge/Pinia-State%20Management-yellow)
![Bootstrap](https://img.shields.io/badge/Bootstrap-UI-7952B3)
![Status](https://img.shields.io/badge/Status-Academic%20Project-blue)

This repository contains the frontend of **Internship Management**, a full-stack web platform designed to simplify intern application handling and internship administration.

The frontend provides the user interface for administrators and interns to manage internship offers, internship requests, supervisors, intern records, forms, and dashboard views.

## Frontend Responsibilities

- Display the administrative dashboard
- Manage internship offers and requests
- Manage interns and supervisors
- Display and handle internship forms
- Provide profile and navigation interfaces
- Connect the UI to backend REST APIs
- Manage application state on the client side
- Provide responsive pages and reusable UI components

## Tech Stack

- Vue.js 3
- Vue Router
- Pinia
- Axios
- Bootstrap 5
- Chart.js
- HTML5
- CSS3
- JavaScript

## Getting Started

### Prerequisites

Make sure you have installed:

- Node.js
- npm

### Clone the repository

```bash
git clone https://github.com/nizarchaouch/gestion-de-stagiaires-frontend.git
cd gestion-de-stagiaires-frontend
```

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run serve
```

### Build for production

```bash
npm run build
```

## Main Pages and Modules

- Home dashboard
- Administrators management
- Interns management
- Supervisors management
- Internship requests management
- Internship form management
- Offers management
- Admin profile page
- Charts and statistics components

## Project Structure

```bash
gestion-de-stagiaires-frontend/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   ├── router/
│   ├── stores/
│   ├── views/
│   ├── App.vue
│   └── main.js
├── package.json
└── README.md
```

## Related Repository

Backend repository: https://github.com/nizarchaouch/gestion-de-stagiaires-backend.git

## Notes

- The frontend communicates with the backend running locally on `http://localhost:8081`.
- Routing is handled with **Vue Router**.
- State management is handled with **Pinia**.
- UI components are organized into reusable folders for tables, modals, forms, offers, charts, and navigation.

## Author

**Nizar Chaouch**
