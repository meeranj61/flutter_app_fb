# Flutter WebView App

This project is a simple Flutter WebView application that loads a website inside a mobile app using the `webview_flutter` package.

---

## Project Overview

* **Project Name:** fb_webview_app
* **Technology Used:** Flutter (Dart)
* **Platform:** Android
* **IDE Used:** VS Code / Android Studio
* **Purpose:** To display a website inside an Android app using a WebView component.

---

## Setup and Installation Steps

Follow these steps to run the project successfully:

### Step 1: Install Flutter

Download Flutter SDK from:
[https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install)

After installation, verify by running:

```bash
flutter doctor
```

Ensure that all required components (Android SDK, Chrome, Visual Studio Code, etc.) are properly configured.

---

### Step 2: Create and Open the Project

If not already created:

```bash
flutter create fb_webview_app
```

Then open the project folder in VS Code or Android Studio.

---

### Step 3: Get All Dependencies

Run the following command inside your project directory:

```bash
flutter pub get
```

This installs all the required Flutter packages, including:

* webview_flutter

---

### Step 4: Clean Old Builds (Recommended)

Before running, clean the project:

```bash
flutter clean
```

Then fetch dependencies again:

```bash
flutter pub get
```

---

### Step 5: Run the Project

Use the following command to start the app:

```bash
flutter run
```

You can choose:

* Android Emulator
* Physical Device (with USB Debugging Enabled)

---

## Main Features

* Displays any website URL inside the mobile app
* Uses Flutter WebView widget for browsing
* Simple, responsive, and lightweight
* Runs smoothly on Android devices

---

## Packages Used

| Package Name    | Version | Purpose                                    |
| --------------- | ------- | ------------------------------------------ |
| webview_flutter | 3.0.4   | To embed a web page inside the Flutter app |

---

## What Was Completed

* Flutter installed and configured successfully
* Android SDK setup completed
* Required packages added (webview_flutter)
* Project build and run tested
* WebView integrated and working correctly
* App successfully launched on emulator

---

## Author

**Developed by:** Syed

