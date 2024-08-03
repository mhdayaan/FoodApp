# Food Runner App

Welcome to the Food Runner App repository! This project is a food ordering application developed using Kotlin. It allows users to browse food items, place orders, and manage their profiles.

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [File Structure](#file-structure)
7. [Contributing](#contributing)

## Features

- **Browse Food Menu**: View a list of available food items.
- **Order Placement**: Select food items and place orders.
- **User Management**: Register, log in, and manage user profiles.
- **Order History**: View previous orders and their details.
- **Responsive Design**: User-friendly interface optimized for mobile devices.

## Requirements

- Kotlin 1.5 or higher
- Android SDK 30 or higher
- Android Studio 4.1 or higher

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mhdayaan/FoodApp
   cd FoodApp
   ```

2. Open the project in Android Studio:
   - Launch Android Studio.
   - Select "Open an Existing Project."
   - Navigate to the `FoodApp` directory and open it.

3. Sync Gradle:
   - Android Studio will prompt to sync Gradle. Allow it to do so to download necessary dependencies.

4. Build and Run:
   - Connect an Android device or start an Android emulator.
   - Click "Run" in Android Studio to build and deploy the app on your device.

## Configuration

1. Update local properties:
   - Ensure the `local.properties` file contains the correct path to your Android SDK.

2. Build Configuration:
   - The `build.gradle` files manage project dependencies and configurations. Make sure they are updated to match your development environment.

## Usage

1. Launch the app on your Android device or emulator.
2. Register a new account or log in with existing credentials.
3. Browse the food menu, select items, and place your order.
4. View your order history and manage your profile from the app's interface.

## File Structure

- `app/`: Contains the main application source code.
- `build/`: Contains build outputs and related files.
- `gradle/wrapper/`: Contains Gradle wrapper files.
- `Food Runner.iml`: IntelliJ IDEA module file.
- `build.gradle`: Gradle build configuration for the app module.
- `gradle.properties`: Gradle project properties.
- `gradlew`/`gradlew.bat`: Gradle wrapper scripts for Unix and Windows.
- `local.properties`: Local configuration for Android SDK path.
- `settings.gradle`: Gradle settings for the project.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

1. Fork the repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push to the branch and open a pull request.
