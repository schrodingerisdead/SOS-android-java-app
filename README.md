# SOS-android-java-app
The SOS Mobile Application for Android is designed to provide emergency assistance functionality triggered by shaking gestures. When a user shakes their device, the application sends SMS alerts with the user's location to predefined emergency contacts. This project leverages foreground services, permissions management, and integration with Google Play Services for reliable location tracking.
## Features
* **Shake Detection**: Detects shaking gestures using the device's accelerometer.
* **SMS Alerts**: Automatically sends emergency SMS messages to predefined contacts.
* **Foreground Service**: Ensures the application remains active in the background to quickly respond to emergency situations.
* **Permissions Management**: Dynamically manages permissions for location access and SMS sending.
* **User Interface**: Provides a user-friendly interface for managing emergency contacts and settings related to SOS functionality.
## Technologies Used
* **Android SDK**
* **Java**
* **SQLite** (for local storage of contacts)
* **Google Play Services** (for location tracking)