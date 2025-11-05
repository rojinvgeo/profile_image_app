# Profile Image App

A simple Flutter application to **pick, upload, and display a profile image locally**.  
This project does **not use Firebase** — everything is saved locally on the device for offline access.

---

## 🛠️ Features

- Pick an image from the device gallery
- Upload (save) the image locally
- Display the uploaded image in a **rounded avatar**
- Shows **success/error messages** on upload
- Saves image permanently using `SharedPreferences` and `path_provider`
- Fully **offline** functionality

---

## 📚 What I Learned

- Handling **image picking** in Flutter using `image_picker`
- Saving and reading files **locally** with `path_provider`
- Persistent storage using `SharedPreferences`
- Managing **state** in a simple Flutter app
- Displaying **SnackBar messages** for user feedback
- Building **centered and responsive UI** with `CircleAvatar` and buttons

---

## 💻 Tech Stack

- **Flutter** & **Dart**
- Packages:
  - `image_picker`
  - `path_provider`
  - `shared_preferences`
- No backend or Firebase needed (local storage only)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/rojinvgeo/profile_image_app.git
2. Navigate into the project directory:
```bash
cd profile_image_app
```
3. Get dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```


