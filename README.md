## React Quiz App

A simple and interactive quiz application built with React as part of Jonas Schmedtmann's React course.  
It uses a "fake API" powered by `json-server` to fetch quiz questions and manages state using the `useReducer` hook.

## Live Demo

[Click here to view the live project](https://minaafzli.github.io/Quiz-App/)

## Technologies Used

- React (Create React App)
- useReducer, useEffect
- json-server (mock API)
- CSS with media queries (responsive design)
- gh-pages (for deployment)

## Features

- Multiple-choice quiz with live scoring
- Question-by-question progress
- Timer for each quiz session
- Final results with a restart option
- Mobile and desktop responsive layout
- Fully local development with fake API

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/minaafzli/Quiz-App.git
cd Quiz-App

```

2. Install dependencies:

```bash
npm install

```

3. Start the fake API server (uses json-server):

```bash
npm run server
```

4. In a second terminal tab, start the React app:

```bash
npm start

```

The app runs on `http://localhost:3000`  
The mock API runs on `http://localhost:8000`
