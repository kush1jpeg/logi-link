# React App Setup

This project is a React-based web application that includes multiple components and routing with React Router.

## Requirements

Ensure you have the following installed:

- **Node.js** (Latest LTS recommended)
- **npm** or **yarn** (Comes with Node.js)
- **Python** ( for running the backend)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/kush1jpeg/logi-link-HackStreet.git
   cd logi-link-HackStreet
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

   or if using yarn:

   ```sh
   yarn install
   ```

## Running the Application

### Starting the React App

To start the React development server, run:

```sh
npm start
```

or using yarn:

```sh
yarn start
```

The React app will be available at `http://localhost:3000` by default.

### Running Backend Separately

If your application interacts with a backend, ensure that it runs on a different port. Typically:

- React frontend runs on **port 3000**
- Backend (Flask, Node.js, etc.) should run on **a different port** (e.g., 5000, 8000)

Make sure no other applications are running on the ports assigned to your React and backend servers to avoid conflicts.

### Running the Python Backend

If using a Flask backend, follow these steps:

1. Navigate to the backend directory (if applicable):
   ```sh
   cd my-app/src/ShittyAI/Flask
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install flask flask-cors flask-sqlalchemy google-generativeai flask-jsonify
   ```
4. Start the Flask server:
   ```sh
   python3 flasktest.py
   ```

Ensure your Flask app runs on a different port than the React app ( http://localhost:5000 ).

## Technologies Used

- **React** (Frontend framework)
- **React Router** (For routing)
- **Bootstrap** (For styling)
- **Flask** (For backend)


## Project Contributors  

### React.js Development  
**Kushagra**  
[🔗 LinkedIn Profile](https://www.linkedin.com/in/kushagra-gupta-62312927a/)  

### Chatbot using Python and Flask  
**Ojas**  
[🔗 GitHub Repository](https://github.com/ultfone/Gemini_Flask)  

### UI/UX Design  
**Zeeshan**  
[🔗 GitHub Profile](https://github.com/LeeFred3042U)  

*(Easter Egg: Click the YouTube button in the footer of the website!)*  
