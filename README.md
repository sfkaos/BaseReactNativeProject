This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

>**Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Update the app

![DALL·E_2024-10-22_13_50_43_-_A_React_Native_app_mockup_showing_two_screens__The_Home_screen_has_a_welcome_message_and_navigation_bar_at_the_bottom_with_two_tabs__Home_and_Profile](https://github.com/user-attachments/assets/278aee96-9d7f-43c5-88c2-598d1af795cf)

## Create a Profile Screen:
Develop a new Profile screen that will display the user's basic information: avatar, name, and email.
Ensure the screen is added to the application’s navigation flow.
## Set Up Navigation:
Implement React Navigation to facilitate navigation between the existing Home screen and the new Profile screen.
If not already configured, install and set up react-navigation, ensuring the app can handle screen transitions.
Add a Bottom Tab Navigator with two tabs: Home and Profile, to allow switching between the screens.
## Integrate API for Fetching User Data:
On the Profile screen, fetch user data from the API endpoint:
https://jsonplaceholder.typicode.com/users/1
Automatically fetch the data when the Profile screen is mounted and display the user’s avatar, name, and email without requiring manual intervention from the user.
## Manage State and Lifecycle:
Use React’s useState and useEffect hooks to manage the state of the fetched data.
Ensure that the data is fetched when the Profile screen loads (using useEffect) and displayed on the screen as soon as the data is available.
## Enhance the UI:
Style the Profile screen to neatly display the user information (name, email, and avatar) using React Native components like Text, Image, and View.
Make sure the layout is clean and responsive across different screen sizes.
## Integrate app with Firebase Cloud Firestore
Using Cloud Firestore is free when you sign up with Firebase - use an existing login or create a new login and integrate the app with Firebase Cloud Firestore (not the Firebase Realtime Database)
## Design your own User Profile form in the app
This is where you can be creative. Give the user the ability to update their profile information within the app.
Design a button and place it wherever you think it makes sense so that when a user clicks on it a form appears where they can see their current profile information and they can update it.
As part of this step you will need to do several things:
1. Create a Firestore schema to hold the user profile information (requires Firebase Cloud Firestore integration above)
2. Design a button for editing the profile
3. Adding a new screen for updating profile information - can be a pop-up, a separate screen, or uses the current screen and makes the input fields editable - this is up to you.
4. Allow users to input data into input fields
5. Save data to Firebase Cloud Firestore

