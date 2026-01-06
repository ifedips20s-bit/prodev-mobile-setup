# 📱 ProDev Mobile App – First App

## Objective
Set up a mobile application using the **Expo Router template**, modify the home screen, and understand the file structure and behavior of a React Native Expo project.

---

## Project Setup

### 1. Navigate to Project Directory

```bash
cd ~/desktop/prodev-mobile-setup
mkdir prodev-mobile-app-0x00
cd prodev-mobile-app-0x00

2. Initialize Expo Project

Create a new Expo project using the latest Expo Router template:

npx create-expo-app@latest .


Choose the default Expo Router template

Dependencies are installed automatically

Project scaffold is created

3. Explore Project Structure

Key directories and files:

app/
├── (tabs)/
│   └── index.tsx      # Home screen
├── _layout.tsx        # Root layout
constants/
└── Colors.tsx         # App color definitions
assets/                # Images, fonts, icons
package.json
README.md


Modify the Home Screen

File: app/(tabs)/index.tsx

Change the default text:

<Text>Welcome!</Text>


to:

<Text>First App Created</Text>


Save the file. The app will hot reload automatically.


Run and Test Application

Start the development server:

npx expo start


iOS: Scan the QR code with Camera app

Android: Scan the QR code using Expo Go

Web: Press w in the terminal

Your home screen should now display “First App Created”.


