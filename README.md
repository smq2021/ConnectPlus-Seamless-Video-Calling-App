# ConnectPlus: Seamless Video Calling App

## Overview

**ConnectPlus** is an Android video calling application designed to enhance business communication by providing a seamless and efficient platform for voice and video calls. The app focuses on streamlining remote meetings and team collaboration, making it easier for users to connect and communicate effectively.

## Features

- **User-Friendly Interface**: Intuitive design that allows users to navigate easily and initiate calls with minimal effort.
- **Voice and Video Calling**: Supports both voice and video calls, ensuring flexibility in communication.
- **Search Functionality**: Quickly find and connect with colleagues or clients using the search feature.
- **Real-Time Communication**: Experience low-latency calls for smooth and uninterrupted conversations.
- **Integration with ZEGOCLOUD**: Utilizes ZEGOCLOUD's SDK for reliable and high-quality video calling capabilities.

## Technologies Used

- **Programming Language**: Kotlin
- **Framework**: Android SDK
- **Backend Services**: ZEGOCLOUD for real-time communication
- **Database**: Firebase for user authentication and data storage
- **Build Tools**: Gradle for dependency management and project configuration

## Installation

To set up the ConnectPlus project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/smq2021/ConnectPlus-Seamless-Video-Calling-App.git
   ```

2. **Open the Project**:
   Open the project in Android Studio.

3. **Configure Firebase**:
   - Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
   - Add your Android app to the Firebase project and download the `google-services.json` file.
   - Place the `google-services.json` file in the `app/` directory of your project.

4. **Add ZEGOCLOUD SDK**:
   - Follow the instructions on the [ZEGOCLOUD documentation](https://zegocloud.com/docs) to set up your account and obtain the necessary credentials (App ID and App Sign).
   - Update the `AppConstants.kt` file with your ZEGOCLOUD credentials.

5. **Build the Project**:
   - Sync the Gradle files and build the project in Android Studio.

6. **Run the App**:
   - Connect an Android device or use an emulator.
   - Run the app from Android Studio.

## Usage

1. **Login**: Upon launching the app, users can log in using their credentials.
2. **Initiate Calls**: Use the search functionality to find users and initiate voice or video calls.
3. **Join Meetings**: Users can join scheduled meetings seamlessly through the app.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **ZEGOCLOUD**: For providing the SDK that powers the video calling functionality.
- **Firebase**: For user authentication and data management.
- **Android Developers**: For the extensive documentation and resources that made this project possible.

