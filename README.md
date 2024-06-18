Adventure Party

## iOS Emulator Setup
1. Open up the Mac App Store, search for Xcode, and click install (or update if you have it already).
    - If you're unable to update, it is because your operating system might be out of date. We recommend updating your operating system to the latest version and then updating Xcode.
2. Open Xcode, then go to Settings -> Locations -> Command Line tools. Ensure the most recent version is installed, if it's not, install it.
3. Create a simulator device by going to Xcode -> Open Developer Tool -> Simulator. Then navigate to File -> New Simulator.
    - You can name the device anything. Choose any modern iPhone.
4. You can confirm that the previous steps worked and downloaded correctly if the command `xcrun simctl list devices` in your terminal doesn't throw any errors and lists your newly created simulator
5. [You can sanity check this setup and learn more at the Expo documentation](https://docs.expo.dev/workflow/ios-simulator/).

## Android Emulator Setup
1. [Please follow the Expo documentation listed for your device.](https://docs.expo.dev/workflow/android-studio-emulator/)

## App Setup
npm install
npx expo install react-native-web react-dom @expo/metro-runtime

