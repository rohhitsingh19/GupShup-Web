# GupShup - Real-Time Chat Application

GupShup is a modern, real-time chatting application built to provide seamless communication. It features user authentication, responsive design, and real-time messaging with a robust backend to ensure scalability and reliability.

## Features

- **Real-Time Messaging:** Instant communication powered by `socket.io`.
- **User Authentication:** Secure authentication using JWT (JSON Web Tokens).
- **Responsive UI:** Built with `React.js`, `TailwindCSS`, and `daisyUI` for a visually appealing and mobile-friendly interface.
- **Media Uploads:** Integrated with Cloudinary for efficient image and file management.
- **Scalable Backend:** Developed with `Node.js`, `Express.js`, and `MongoDB` for a high-performing backend.
- **API Testing:** APIs tested and validated using Postman.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/username/gupshup-chat-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd gupshup-chat-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     JWT_SECRET=your_jwt_secret
     ```
5. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. Register or log in to the application.
2. Create or join chat rooms to communicate with other users in real time.
3. Upload and share media files during chats.

## Technologies Used

### Frontend
- **React.js**
- **TailwindCSS**
- **daisyUI**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB**
- **Socket.io**
- **Cloudinary**

### Testing
- **Postman**
![Screenshot 2025-01-22 112041](https://github.com/user-attachments/assets/20befc15-b423-4a48-b8ba-4dac2241cfef)

![Screenshot 2025-01-22 112109](https://github.com/user-attachments/assets/18919491-8627-4e4f-a16f-faf5dec3b27e)

