
<div align="center">
  <h3 align="center">MERN Blog Project</h3>
  <p align="center">A full-stack blog application built using the MERN stack.</p>
</div>

## Technologies Used

- **Frontend:**
  - ![React.js](https://img.shields.io/badge/React.js-005400?style=for-the-badge&logo=reactdotjs&logoColor=white) React.js
- **Backend:**
  - ![Node.js](https://img.shields.io/badge/Node.js-f084e0?style=for-the-badge&logo=nodedotjs&logoColor=white) Node.js
- **Database:**
  - ![MongoDB](https://img.shields.io/badge/MongoDB-a082e0?style=for-the-badge&logo=mongo&logoColor=white) MongoDB (with Mongoose ODM)
- **Authentication:** bcrypt.js, JWT (JSON Web Tokens)
- **File Upload:** Multer
- **Other Libraries:** cors, cookie-parser, fs

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Install Dependencies**

    To install the project dependencies, navigate to your project folder in your terminal and run the following commands:

    ```bash
    cd <project_folder>
    npm install
    cd client
    npm install
    ```

3. **Set up Environment Variables**

    Create a `.env` file in the root directory of your project and define the following variables:

    ```makefile
    PORT=4000
    MONGO_URI=<your_mongodb_uri>
    JWT_SECRET=<your_jwt_secret>
    ```

4. **Run the Development Server**

    To run the development server, execute the following command in your terminal from the root directory of your project:

    ```bash
    npm run dev
    ```

    This will concurrently start the backend server and the React development server.

5. **Access the Application**

    Once the development server is running, open your web browser and go to [http://localhost:3000](http://localhost:3000) to access the application.
