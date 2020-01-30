# Working with React Native

Assuming that you have Node 10 LTS or greater installed, you can use npm to install the Expo CLI command line utility:

```sh
npm install -g expo-cli
```

Then run the following commands to create a new React Native project called "AwesomeProject":

```sh
expo init AwesomeProject

cd AwesomeProject
npm start # you can also use: expo start
```

This will start a development server for you.

## Running your React Native application

Install the Expo client app on your iOS or Android phone and connect to the same wireless network as your computer. On Android, use the Expo app to scan the QR code from your terminal to open your project. On iOS, follow on-screen instructions to get a link.

## Modifying your app

Now that you have successfully run the app, let's modify it. Open ```App.js``` in your text editor of choice and edit some lines. The application should reload automatically once you save your changes.

## Running your app on a simulator or virtual device

Expo CLI allows you to run your React Native app on a physical device without setting up a development environment. If you want to run your app on the iOS Simulator or an Android Virtual Device, please refer to the instructions for "React Native CLI Quickstart" to learn how to install Xcode or set up your Android development environment.

Once you've set these up, you can launch your app on an Android Virtual Device by running ```npm run android```, or on the iOS Simulator by running ```npm run ios``` (macOS only).