# ChaTop - Frontend

Welcome to the frontend of ChaTop, a rental listing management application. This project is developed with Angular. For backend services, refer to the [ChaTop Backend Repository](https://github.com/maximedrouault/ChaTop-back).

## Prerequisites

- **Node.js 22 or higher**: [Download Node.js](https://nodejs.org/).

## Installation and Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/maximedrouault/ChaTop-front.git
   cd ChaTop-front
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start the application**:

   ```bash
   npm start
   ```

   The application will be available at: `http://localhost:4200`.

## Environment Configuration

Ensure that the `environment.ts` file in the `src/environments` directory contains the correct configurations for your development environment, particularly the backend API URL.

## Additional Resources

- **Mockoon**: If you use Mockoon for API simulation, you can load the environment `resources/mockoon/rental-oc.json` directly in Mockoon. [Download Mockoon](https://mockoon.com/download/).

- **Postman Collection**: A Postman collection is available in `resources/postman/rental.postman_collection.json` to test the application's requests. [Import Guide](https://learning.postman.com/docs/getting-started/importing-and-exporting-data/#importing-data-into-postman).

## Project Structure

- **src/**: Contains the application's source code.
  - **app/**: Main modules and components.
  - **environments/**: Configuration files for different environments.
