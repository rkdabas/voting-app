# voting-app
This is a backend application for a voting system where users can vote for candidates. It provides functionalities for user authentication, candidate management, and voting.
## Features
* User sign up and login with Aadhar Card Number and password
* User can view the list of candidates
* User can vote for a candidate (only once)
* Admin can manage candidates (add, update, delete)
* Admin cannot vote
## Tech used
* Node.js
* Express.js
* MongoDB
* JSON Web Tokens (JWT) for authentication
# API Endpoints
## Authentication
### Signup
* POST /signup: Sign up a user
### Login
* POST /login: Login a user
## Candidates
### Get Candidates
* GET /candidates: Get the list of candidates
### Add Candidates
* POST /candidates: Add a new candidate (Admin only)
### Update Candidates
* PUT /candidates/:id: Update a candidate by ID (Admin only)
### Delete Candidates
* DELETE /candidates/:id: Delete a candidate by ID (Admin only)
## Voting
### Get Vote Count
* GET /candidates/vote/count: Get the count of votes for each candidate
### Vote for Candidate
* POST /candidates/vote/:id: Vote for a candidate (User only)
## User Profile
### Get Profile
* GET /users/profile: Get user profile information
### Change the password
* PUT /users/profile/password: Change user password



