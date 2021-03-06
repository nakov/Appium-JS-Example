# Appium-JS-Example

Example of **Appium UI automated tests** for Android app with **JavaScript** and **Mocha**:

![image](https://user-images.githubusercontent.com/1689586/128168121-9c81adec-d325-420e-a20c-1c92a462e7cc.png)

# Goals

Writing Appium mobile UI automated tests for the ContactBook sample Android app:
https://github.com/nakov/ContactBook-AndroidClient

# Running the Appium Tests

1. Restore the **Node.js dependencies**: ```npm install```
2. Start the **Android emulator** - https://developer.android.com/studio/run/emulator
3. Start **Appium desktop** and bind it to the IPv6 loopback address `::1` - https://github.com/appium/appium-desktop
4. Run the **Mocha tests**: ```npm test```

# Expected Test Results

![image](https://user-images.githubusercontent.com/1689586/128169529-48d931a3-ea0c-4be0-b609-ec959a646109.png)
