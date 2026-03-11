# Contact Manager API

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- Nodemon
- dotenv

## Project Structure
Contact-Manager-NM

config/
dbConnection.js

controllers/
contactController.js

models/
contactModel.js

routes/
contactRoutes.js

middleware/
errorHandler.js

server.js  
package.json  
.env

## Installation Steps
1. Clone the repository
2. Open the project folder
3. Install dependencies using the following command

npm install

## Environment Variables
Create a `.env` file and add the following:

PORT=5000  
CONNECTION_STRING=mongodb://127.0.0.1:27017/contact-manager

## Running the Project
Start the server using:

npm run dev

The server will run on:

http://localhost:5000

## API Endpoints

Get All Contacts  
GET /api/contacts

Create Contact  
POST /api/contacts

Get Single Contact  
GET /api/contacts/:id

Update Contact  
PUT /api/contacts/:id

Delete Contact  
DELETE /api/contacts/:id

## Example JSON Request

{
"name": "John Doe",
"email": "john@email.com",
"phone": "123456789"
}

## Testing the API
The API can be tested using Postman.

Base URL:
http://localhost:5000/api/contacts
