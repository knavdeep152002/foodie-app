# WBD Project - Foodie App

Foodie, a social media exclusively for posting and sharing food content for the foodies by the foodies.

## Group No 22

- Gireesh Kumar Reddy Chumdi (S20190010036)

-  Sai Bhargav Reddy Kanala (S20190010083)

- Khadyothan Dasari (S20190010040)

- Chandra Kiran G (S20190010029)

- Navdeep Konkipudi (S20190010099)



## Tech Stack Used for the App

#### Frontend

- ReactJS

- TypeScript

- Redux

- Axios

#### Backend

- Node

- MongoDB

- SocketIO

- Express JS

- Passport JS

- GCS



## Instructions

1. Unzip the folder `foodie-app`

2. Install the required modules for both frontend and backend through the following command:
   
   ```bash
   npm run init-project
   ```

3.  Download and install MongoDB locally.

4. Create `.env-dev` to store env variables for running the development server and set the following contents:
   
   ```python
   MONGODB_URI=<mongodb uri | default local = mongodb://localhost:2717 >
   DB_NAME=<foodie
   PORT=9000
   CLIENT_URL=http://localhost:3000
   SESSION_SECRET=<any secret key>
   SESSION_NAME=foodie
   FIREBASE_PROJECT_ID=<firebase project id found on your firebase config settigs>
   FIREBASE_STORAGE_BUCKET_URL=<firebase bucket url found on your firebase config settigs>
   CLOUDINARY_NAME=<Name>
   CLOUDINARY_API_KEY=<API Key>
   CLOUDINARY_API_SCERET=<API Secret>
   ```

5. Finally run the project using:
   
   ```bash
   npm start
   ```
   
   
