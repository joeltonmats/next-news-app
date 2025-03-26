# Next Routing Rendering

This repository contains the code and resources for the "Next Routing Rendering" project. It is a simple application designed to demonstrate the basics of routing and rendering in the Next.js framework.

## Tech Stack

- **Next.js**: A React framework for server-side rendering and static site generation.
- **React**: A JavaScript library for building user interfaces.
- **CSS Modules**: A CSS file in which all class and animation names are scoped locally by default.

## Features

- Dynamic routing with Next.js.
- Intercepted routes for modals and nested layouts.
- Server-side rendering and static generation.
- Clean and modular folder structure for scalable applications.

## Getting Started

To get started with this project, clone the repository and install the dependencies:

```bash
git clone git@github.com:your-username/next-routing-rendering.git
cd next-routing-rendering
npm install
```

## Development Mode

Run the development server:

```bash
npm run dev
```

Open http://localhost:3000 with your browser to see the result.

## Production Mode

Build and start the production server:

```bash
npm run build
npm start
```

Open http://localhost:3000 with your browser to see the result.

## Folder Structure

- app/: Contains the Next.js App Router structure, including dynamic routes, layouts, and intercepted routes.
- components/: Reusable React components used throughout the application.
- public/: Static assets such as images and fonts.

## Key Concepts Demonstrated

- Dynamic Routes: Using [slug] and [[...filter]] for flexible routing.
- Intercepted Routes: Leveraging (.) syntax for modals and overlays.
- Layouts: Nested layouts for consistent UI structure.
- Server-Side Rendering: Fetching data and rendering pages on the server.
