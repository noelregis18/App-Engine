# App Engine - Delivery Routing Application

This project is a delivery routing application built with a Java backend (Google App Engine) and a React frontend. It helps optimize delivery routes and manage delivery logistics.

## Project Structure

The project consists of two main components:

- **Backend API**: Java-based API running on Google App Engine
- **Frontend**: React-based web application for route visualization and management

## Prerequisites

- Java 8 or higher
- Node.js and npm
- Maven
- Google Cloud SDK (for deployment)

## Installation

### Backend Setup

1. Clone the repository
2. Navigate to the project root directory
3. Build the project using Maven:
   ```
   mvn clean package
   ```

### Frontend Setup

1. Navigate to the React application directory:
   ```
   cd src/deliveryrouting
   ```
2. Install dependencies:
   ```
   npm install
   ```

## Running the Application

### Backend

To run the backend locally:

```
mvn appengine:run
```

The API will be available at `http://localhost:8080`

### Frontend

To start the React development server:

```
cd src/deliveryrouting
npm start
```

The application will be available at `http://localhost:3000`

## Available Scripts

In the frontend project directory, you can run:

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from create-react-app

## Deployment

### Backend Deployment

To deploy the backend to Google App Engine:

```
mvn appengine:deploy
```

### Frontend Deployment

Build the React application and deploy it to your preferred hosting service:

```
cd src/deliveryrouting
npm run build
```

## Technologies Used

- **Backend**:
  - Java 8
  - Google App Engine
  - Maven
  - Servlet API
  - GSON (for JSON processing)

- **Frontend**:
  - React
  - React Router
  - Google Maps API integration
  - React Geocode

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.