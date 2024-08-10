# Navigation Project

This project consists of a frontend built with Vite and a backend built with Node.js.

## Project Structure
```
navigation/
├── frontend/     # Vite-based frontend
└── backend/      # Node.js-based backend
```

## Frontend

The frontend is built using Vite, a fast build tool for modern web development.

### Setup

1. Navigate to the frontend directory:

```
cd navigation/frontend
```

2. Install dependencies:

```
npm install
```

3. Configure the config.env file:

```
VITE_MAP_API_KEY= your api key form google map 
VITE_WEATHER_API_KEY= your api key form openweathermap.
```

3. Run the development server:

```
npm run dev
```

For more details, see the [Frontend README](./frontend/README.md).

## Backend

The backend is built using Node.js.

### Setup

1. Navigate to the backend directory:

```
cd navigation/backend
```

2. Install dependencies:

```
npm install
```

3. Start the server:
```
npm run dev
```

For more details, see the [Backend README](./backend/README.md).

## Development

To work on the full stack application:

1. Start the backend server
2. In a new terminal, start the frontend development server
3. Make sure the frontend is configured to make API calls to the correct backend URL



