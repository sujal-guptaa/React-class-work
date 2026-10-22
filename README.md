# React Class Work

This repository contains a React learning project built with Vite. It includes hands-on practice for core React concepts such as components, routing, state management, hooks, forms, API handling, and UI rendering.

## Project Overview

The app is organized inside the `ReactJS-main/` folder and demonstrates a variety of React topics used during class practice, including:

- React components and props
- State and lifecycle management
- React Router navigation
- useState, useEffect, useMemo, useCallback, useReducer, and useRef
- Form handling and validation
- Search params and dynamic routes
- Bootstrap-based styling
- Displaying JSON data and mock API interactions

## Tech Stack

- React
- Vite
- JavaScript
- React Router DOM
- Bootstrap
- Axios
- JSON Server

## Repository Structure

```bash
React-class-work/
├── ReactJS-main/
│   ├── public/
│   ├── src/
│   ├── db.json
│   ├── package.json
│   ├── vite.config.js
│   ├── index.html
│   ├── eslint.config.js
│   └── README.md
├── README.md
└── .gitignore
```

## Features Included

- Home page and navigation bar
- Registration form page
- About/contact pages
- Course and product pages with route parameters
- Timer and search param examples
- Reusable components and hooks-based examples
- Mock backend data using `db.json`

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/sujal-guptaa/React-class-work.git
```

2. Open the app folder:

```bash
cd React-class-work/ReactJS-main
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

5. Open the local URL shown in the terminal to view the app.

## Build for Production

```bash
npm run build
```

## Optional: Run the mock API

This project includes a `db.json` file that can be used with JSON Server for mock data:

```bash
npx json-server --watch db.json
```

## Notes

This project is primarily a React practice repository and demonstrates both beginner and intermediate concepts used in front-end development.

## License

This project is for educational purposes.
