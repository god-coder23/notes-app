📝 Notes App

A clean and simple notes app built with React Native. It lets you quickly create, view, and manage notes without any unnecessary clutter.

✨ What it does
Shows all your notes in a neat dashboard
Lets you add new notes easily
Displays timestamps so you know when notes were created
Works smoothly on mobile devices
Lightweight and fast
🛠 Built with
React Native
React
TypeScript
Jest (for testing)
Babel & Metro
📦 Main dependencies
react-native-safe-area-context
react-native-svg
lucide-react-native
🚀 How to run it
1. Clone the project
git clone https://github.com/god-coder23/notes-app.git
cd notes-app
2. Install dependencies
npm install
3. Run the app

Android

npm run android

iOS

npm run ios

Start Metro:

npm start
📁 Project structure
src/
  Screens/
    Dashboard.jsx
    AddNotes.jsx
  Home.jsx
App.jsx
📱 Features explained
Dashboard
Displays all notes
Shows timestamps
Easy navigation
Add Notes
Simple input field
Supports longer text
Saves notes instantly
🧪 Testing
npm test
🔧 Useful commands
npm run android – run on Android
npm run ios – run on iOS
npm start – start bundler
npm test – run tests
🐛 Common fixes

Metro issues

npm start -- --reset-cache

Android issues

cd android
./gradlew clean
cd ..
npm run android

iOS issues

cd ios
rm -rf Pods Podfile.lock
pod install
cd ..
npm run ios
