# Hire Hub (MemJobi Job Portal Client)

A comprehensive Android native application designed for job seekers to browse, apply for jobs, and communicate with employers in real-time. The app relies on a robust Firebase backend for its core functionalities.

---

## 🚀 Features

- **User Authentication:** Secure Login and Sign-Up flows using Firebase Authentication.
- **Job Browsing & Application:** Users can browse available job postings on the Home screen and apply directly via the app.
- **Real-Time Chatting:** In-app messaging system allowing users to communicate directly with employers or other users (powered by Firebase Firestore).
- **User Profiles:** Dedicated profile section to manage user details and track applications.
- **Push Notifications:** Integrated Firebase Cloud Messaging (FCM) to keep users updated on their application statuses and new messages.
- **Polished UI/UX:** 
  - Smooth animations using **Lottie**.
  - Skeleton loading states using **Shimmer**.
  - Efficient image caching and loading with **Glide**.
  - Material Design and ViewBinding.

---

## 🛠️ Tech Stack & Libraries

- **Language:** Kotlin
- **Architecture & UI:** Android SDK (Minimum API 24, Target API 34), Material Design, and XML Layouts with ViewBinding.
- **Backend as a Service (BaaS):** 
  - **Firebase Authentication** (User management)
  - **Firebase Firestore** (Real-time NoSQL database for jobs and chats)
  - **Firebase Storage** (For user avatars, resumes, and media)
  - **Firebase Cloud Messaging** (Push notifications)
  - **Firebase Analytics**
- **Dependencies:**
  - `com.github.bumptech.glide:glide` (Image Loading)
  - `com.facebook.shimmer:shimmer` (Loading UI effects)
  - `com.airbnb.android:lottie` (Vector animations)
  - `de.hdodenhof:circleimageview` (Circular imagery)

---

## ⚙️ Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing:

### Prerequisites
- [Android Studio](https://developer.android.com/studio) installed.
- An active [Firebase Project](https://console.firebase.google.com/).

### Installation Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/kunal88ch/Hire-Hub.git
   ```
2. **Open the project** in Android Studio.
3. **Configure Firebase:**
   - Create an Android App in your Firebase console matching the package name `com.talhaatif.jobportalclient`.
   - Download the generated `google-services.json` file.
   - Place your `google-services.json` inside the `app/` directory of the cloned project.
   - Run the project once via a USB device or AVD. Ensure your Firebase Firestore, Storage, and Authentication services are enabled in your console.
4. **Sync Gradle files** and build your project.
5. **Run the app** on an Android Emulator or physical device.

---
*Created and maintained as part of the Hire-Hub project.*
