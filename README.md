# MERN-Starter
A starter project for MERN (MongoDB, ExpressJS, ReactJS and NodeJS) stack with Docker

## How to run
1. Clone the repository
2. Create a `.env` file in the `backend` directory and add the following environment variables:
```
MONGO_URI=<your_mongo_uri>
```
3. Run `. up.sh` in root directory with Git Bash to start both the backend and frontend servers inside a Docker container<br>
	- Frontend: [http://localhost:3000](http://localhost:3000)<br>
	- Backend: [http://localhost:5000](http://localhost:5000)