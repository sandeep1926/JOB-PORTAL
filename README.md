Job Portal App with MERN Stack
A full-fledged job portal app developed with the MERN (MongoDB, Express.js, React.js, Node.js) stack. It facilitates users to search through job postings, apply for a job, and track their applications hassle-free.

Features
User Authentication: Safe authentication with JWT (JSON Web Tokens) for both employers and job seekers.
Job Listings: Search through an extensive list of job postings retrieved from MongoDB.
Application Management: The job applicant can control their job applications, and the employer can see and manage received applications.
Responsive Design: Provisions a smooth experience across all devices.
Technologies Used
Frontend: React.js, React Router, Bootstrap
Backend: Node.js, Express.js, MongoDB
Authentication: JWT (JSON Web Tokens), Bcrypt (for password hash)
Image Upload: Cloudinary for storing and managing uploaded images
Deployment: Vercel (frontend), Render(backend), MongoDB Atlas (database)
Getting Started
To get a local copy up and running follow these simple steps.

Prerequisites
Node.js installed on your system with latest version or v22.2.0 above
MongoDB Atlas account (or local MongoDB server)
Cloudinary account for image storage
Installation
Clone the repo:
git clone https://github.com/exclusiveabhi/react-job-portal.git
Install NPM packages:
cd react-job-portal
cd backend
npm install
cd.
cd frontend
npm install
If you don't want to modify the.env credentials skip step 4 and proceed to step 5.
Set up environment variables:

Create a config.env file after creating a config folder in the backend directory, with the following variables:
PORT=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
CLOUDINARY_CLOUD_NAME=
FRONT
Replace each value with your own configuration details.

Run the application backend (be in /backend directory) :

node server.js
Run the application frontend (be in /frontend directory) :

npm run dev
Open your browser and go to http://localhost:5173 to see the app.

Contributing
Contributions are welcome and are the lifeblood of the open-source community, making it such an incredible place to learn, be inspired, and create. Any contribution you make is appreciated.
