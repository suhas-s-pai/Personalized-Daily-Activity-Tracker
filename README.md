Personalized Individual Daily Tracker

A simple, elegant daily task tracker built using HTML, CSS, and JavaScript, connected to Firebase Realtime Database for cloud-based storage and live synchronization.

You can add daily activities, mark them as completed, and even get reminders when you miss your scheduled end time — all with a glowing, futuristic UI design.

✨ Features

🧾 Add, view, and manage daily tasks

☁️ Data stored in Firebase Realtime Database (accessible anywhere)

🔄 Live updates (no page refresh needed)

✅ Mark tasks as complete in real-time

🔔 Smart reminders for pending tasks

🎨 Gradient + Glassmorphism UI

🛠️ Technologies Used
Category	Technology
Frontend	HTML, CSS, JavaScript
Backend	Firebase Realtime Database
Hosting (optional)	Firebase Hosting / GitHub Pages
⚙️ Setup Instructions
1️⃣ Create a Firebase Project

Go to Firebase Console

Click Add Project → name it (e.g., Daily Tracker)

Finish setup (Google Analytics optional)

2️⃣ Add a Web App

In your Firebase project, click the </> (Web icon)

Give it a name → click Register App

Copy the config code snippet (it looks like this):

const firebaseConfig = {
  apiKey: "AIzaSy...EXAMPLE",
  authDomain: "yourproject.firebaseapp.com",
  databaseURL: "https://yourproject-default-rtdb.firebaseio.com",
  projectId: "yourproject",
  storageBucket: "yourproject.appspot.com",
  messagingSenderId: "1234567890",
  appId: "1:1234567890:web:abcd1234efgh"
};

3️⃣ Enable Realtime Database

In Firebase, go to Build → Realtime Database

Click Create Database

Choose Start in Test Mode (for now)

Copy your Database URL — it’ll look like:

https://yourproject-default-rtdb.firebaseio.com/

4️⃣ Add Firebase Config to Your Project

Open your index.html file and replace the placeholder config inside:

const firebaseConfig = { ... };


with your own Firebase project’s configuration.
