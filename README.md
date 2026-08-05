# 🔐 Privacy Dashboard - Android Application

[![Kotlin](https://img.shields.io/badge/Kotlin-1.9.0-purple.svg)](https://kotlinlang.org/)
[![Android](https://img.shields.io/badge/Android-API%2034-green.svg)](https://developer.android.com/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/warshia-rubab/PrivacyDashboard)](https://github.com/warshia-rubab/PrivacyDashboard/stargazers)

> A comprehensive Android application designed to help users monitor, manage, and enhance their device privacy settings with an intuitive dashboard interface.

---

## 📱 Overview

**Privacy Dashboard** is a modern Android application that provides users with complete visibility and control over their device's privacy settings. Built with Kotlin and Jetpack Compose, it offers a clean, Material Design interface for managing app permissions, tracking privacy-related activities, and receiving security recommendations.

### 🎯 Key Objectives
- **Monitor** privacy settings and app permissions
- **Manage** sensitive permissions across installed applications
- **Alert** users about potential privacy risks
- **Educate** users about privacy best practices

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔒 **Permission Management** | View and manage all app permissions in one place |
| 📊 **Privacy Dashboard** | Real-time overview of your device's privacy status |
| 🛡️ **Security Recommendations** | Get personalized privacy improvement suggestions |
| 📱 **Permission History** | Track which apps accessed sensitive permissions |
| 🌙 **Dark Mode Support** | Full Material Design with light/dark theme support |
| 🔄 **Real-time Updates** | Instant updates when permission changes occur |
| 📋 **App Categories** | Organized view of apps by permission type |
| 🔔 **Privacy Alerts** | Notifications for suspicious permission usage |

---

## 🎥 Demo Videos

### 📹 1. Terminal Upload Process
[![Terminal Recording](
https://img.shields.io/badge/Watch-Terminal%20Upload-blue?style=for-the-badge&logo=github)](
https://github.com/warshia-rubab/PrivacyDashboard/blob/main/Terminal%20Video.mp4)

*Complete walkthrough of uploading the project to GitHub.*

---

### 📊 2. Application Logs Recording
[![Logs Recording](
https://img.shields.io/badge/Watch-Application%20Logs-orange?style=for-the-badge&logo=android)](
https://github.com/warshia-rubab/PrivacyDashboard/blob/main/Logs%20Video.mp4)

*Real-time logs showing app execution, permission checks, and data flow.*

**What's shown in the logs:**
- ✅ App initialization
  
- 🔍 Permission status checks
  
- 📊 Data monitoring events
  
- 🔄 Background processes
  
- ⚠️ Warning messages (if any)
  
- ✅ Successful operations
  

---

### 🔍 Logs Overview

| Log Level | Count | Description |
|-----------|-------|-------------|
| ℹ️ Info | XX | App initialization and main operations |
| 🟡 Warning | X | Non-critical issues (e.g., deprecated API usage) |
| 🔴 Error | X | Critical issues that need attention |
| 🟢 Success | XX | Successful permission checks and operations |

---

## 🛠️ Technology Stack

| Technology | Version | Purpose |
|------------|---------|---------|
| **Kotlin** | 1.9.0 | Primary programming language |
| **Android SDK** | API 34 (Android 14) | Android framework |
| **Jetpack Compose** | 1.5.0 | UI toolkit |
| **Material Design 3** | 1.2.0 | Design system |
| **Coroutines** | 1.7.0 | Asynchronous programming |
| **ViewModel** | 2.7.0 | Architecture component |
| **LiveData** | 2.7.0 | Data observation |
| **Navigation** | 2.7.0 | In-app navigation |

### Architecture Pattern
- **MVVM** (Model-View-ViewModel) architecture
- **Repository pattern** for data management
- **Dependency Injection** ready (Hilt)

---

## 📸 Screenshots

### 🏠 Privacy Dashboard - Main Screen

| Feature | Description |
|---------|-------------|
| **App Permissions** | Scan and manage app permissions |
| **Camera** | Access camera for photos |
| **Location** | Access your location |
| **Audio** | Record audio |
| **Contacts** | Read your contacts |
| **Files** | Access files and media |




### 📱 App Screenshot

<div align="center">
  <img src="https://github.com/warshia-rubab/PrivacyDashboard/blob/main/App%20.png?raw=true" alt="Privacy Dashboard App" width="300"/>
  <br/>
  <em>Privacy Dashboard - Permission Management</em>
</div>

          *Privacy Dashboard showing app permissions with ON/OFF toggles and status indicators.*


### 🔍 Features Shown

| Permission | Status | State |
|------------|--------|-------|
| 📷 **Camera** | 🟢 **ON** | ENABLED |
| 📍 **Location** | 🟢 **ON** | ENABLED |
| 🎙️ **Audio** | 🔴 **OFF** | DISABLED |
| 👤 **Contacts** | 🟢 **ON** | ENABLED |
| 📁 **Files** | 🟢 **ON** | ENABLED |

---


## 🚀 Getting Started

### Prerequisites

| Requirement | Version |
|-------------|---------|
| Android Studio | Flamingo (2022.2.1) or higher |
| JDK | 17 or higher |
| Android SDK | API 34 |
| Gradle | 8.0+ |

---

### Installation Steps

#### 1. Clone the Repository
```bash
git clone https://github.com/warshia-rubab/PrivacyDashboard.git

cd PrivacyDashboard

2. Open in Android Studio

. Launch Android Studio

. Select File → Open

. Navigate to the cloned directory

. Click OK

3. Sync Gradle

Android Studio will automatically sync dependencies

If not, click File → Sync Project with Gradle Files

4. Build the Project

bash

./gradlew build

5. Run the Application

. Connect an Android device or start an emulator

. Click the Run button (▶️) in Android Studio

```
---

## 📁 Project Structure

```

PrivacyDashboard/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/student/privacy/
│   │   │   │   ├── MainActivity.kt          # Main entry point
│   │   │   │   └── ui/
│   │   │   │       └── theme/               # Material Theme
│   │   │   ├── res/
│   │   │   │   ├── drawable/                # Icons & graphics
│   │   │   │   ├── mipmap/                  # Launcher icons
│   │   │   │   ├── values/                  # Colors, strings, themes
│   │   │   │   └── xml/                     # Backup rules
│   │   │   └── AndroidManifest.xml          # App manifest
│   │   ├── androidTest/                     # Instrumented tests
│   │   └── test/                            # Unit tests
│   ├── build.gradle.kts                      # App-level build
│   └── proguard-rules.pro                    # ProGuard rules
├── gradle/
│   └── wrapper/
│       ├── gradle-wrapper.jar
│       └── gradle-wrapper.properties
├── build.gradle.kts                         # Project-level build
├── settings.gradle.kts                      # Project settings
├── gradle.properties                        # Gradle config
├── gradlew                                  # Gradle wrapper (Unix)
├── gradlew.bat                              # Gradle wrapper (Windows)
└── README.md                                # This file
```
---

## 🧪 Testing

1. Run Unit Tests
   
bash

./gradlew test

2. Run Instrumented Tests
   
bash

./gradlew connectedAndroidTest

---

## 🔧 Configuration

Environment Variables

. Create a local.properties file in the root directory:

= properties

sdk.dir=/path/to/your/android/sdk

. Build Variants

Debug - Development build with debugging enabled

Release - Production build with optimization

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository

2. Create a feature branch: git checkout -b feature/amazing-feature

3. Commit changes: git commit -m 'Add amazing feature'

4. Push to branch: git push origin feature/amazing-feature

5. Open a Pull Request

 ---

## Guidelines:

1. Follow Kotlin coding conventions

2. Write meaningful commit messages

3. Add tests for new features

4. Update documentation accordingly

   ---

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 📞 Contact

Project Lead: Warshia Rubab

GitHub: @warshia-rubab

Email: warshiarubab9427@gmail.com

---

## ⭐ Star this repository if you find it useful!


