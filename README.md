# GoaTourWala - Frontend

The frontend client for the GoaTourWala platform, built with React.js.

## Features
- Interactive Tour Categories and Subcategories
- Custom "Plan Trip" Booking Forms
- Responsive Design for Mobile and Desktop
- Integrated Payment Gateway UI

## Getting Started

### Prerequisites
- Node.js installed on your machine

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gitCommit-Suryansh/goatourwala-frontend.git
   ```
2. Navigate to the directory and install dependencies:
   ```bash
   cd goatourwala-frontend
   npm install
   ```
3. Set up environment variables. Create a `.env` file in the root directory:
   ```env
   # Add your environment variables here
   # Example: REACT_APP_BACKEND_URL=http://localhost:5000
   ```

### Running Locally
To start the development server, run:
```bash
npm start
```
The application will be available at `http://localhost:3000`.

### Building for Production
To create an optimized production build:
```bash
npm run build
```
This will generate a `build/` folder that can be deployed to Vercel, Netlify, or any static hosting service.
