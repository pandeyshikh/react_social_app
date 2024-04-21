React Social Media Platform
Overview
This project is a social media platform built using React.js for the frontend, Express.js for the backend, and MySQL for data storage. It allows users to create profiles, connect with friends, share updates, and interact through comments and likes.

Features
User Authentication: Secure user authentication and authorization mechanisms ensure data privacy and security.
Profile Creation: Users can create personalized profiles with profile pictures and bio information.
Friend Connections: Users can connect with friends and view their activity on the platform.
News Feed: Dynamic news feed generation displays updates from friends in real-time.
Post Sharing: Users can create and share posts with their friends.
Comments and Likes: Interactive features allow users to engage with posts through comments and likes.
Technologies Used
Frontend: React.js, HTML5, CSS3, JavaScript
Backend: Node.js, Express.js
Database: MySQL
Version Control: Git, GitHub
Deployment: AWS, Heroku
Getting Started
Clone the repository:
bash
Copy code
git clone (https://github.com/pandeyshikh/react_social_app/new/master)
Install dependencies for both frontend and backend:
bash
Copy code
cd frontend
npm install

cd ../backend
npm install
Set up the MySQL database by importing the provided schema file.
Configure the backend server by updating the database connection details in backend/config/db.config.js.
Start the frontend and backend servers:
bash
Copy code
cd frontend
npm start

cd ../backend
npm start
Access the application at http://localhost:3000 in your web browser.
