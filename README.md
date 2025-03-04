# Full Stack Real-time Chat Application with Authentication
A modern, full-stack real-time chat application built with React JS and Firebase. It features user authentication, real-time messaging, and a clean UI.

# Features
1. Real-time messaging with Firebase Firestore
2. User authentication using Firebase Auth
3. Light-themed UI with a beautiful background
4. Media sharing (Images, Videos, Documents)
5. Group chats
6. Message encryption for security
7. Notifications

# Tech Stack
1.  Frontend: React JS, Tailwind CSS, Context API
2.  Backend: Firebase Firestore (NoSQL database)
3.  Authentication: Firebase Auth
4.  Real-time Messaging: Firestore real-time updates

# Installation
1.  Clone the repository: git clone https://github.com/rittika-04/chat-app.git
   cd chat-app
2. Install dependencies: npm install  # or yarn install
3. Set up Firebase:
   1.  Create a Firebase project at Firebase Console.
   2.  Enable Firestore Database and Firebase Authentication.
   3.  Get your Firebase config keys.
4.  Configure environment variables: Create a .env file in the root directory and add:
   1. REACT_APP_FIREBASE_API_KEY=your_api_key
   2. REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
   3. REACT_APP_FIREBASE_PROJECT_ID=your_project_id
   4. REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   5. REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   6. REACT_APP_FIREBASE_APP_ID=your_app_id
5.Start the development server: npm start  # or yarn start

# Deployment on Vercel
1.  Install Vercel CLI (if not installed): npm install -g vercel
2.  Login to Vercel:vercel login
3.  Deploy the project:vercel
4.  Follow the terminal instructions to configure and deploy.
5.  After deployment, Vercel will provide a live URL for your app.

# Demo
Check out the live demo: [Chat App]([https://vercel.com/rittika04s-projects/chat-app/F2J413EvU22i7ztfbFTVzcXh63Wp])

# License
This project is licensed under the MIT License.

# Contact
For any inquiries, reach out to me at shaw.rittika15@gmail.com.
