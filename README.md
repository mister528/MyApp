# Notes App (مذكراتي)

A modern, feature-rich notes application for Android with dark theme and Arabic language support.

## Features
- ✅ Simple and user-friendly interface
- ✅ Dark mode design with elegant modern touches
- ✅ Add new notes with title and text content
- ✅ Edit and delete notes
- ✅ Search within notes
- ✅ Sort notes by date (newest) or alphabetically
- ✅ Local data storage using SQLite/Room
- ✅ Splash screen with app logo
- ✅ Full Arabic language support
- ✅ Lightweight and fast performance

## Technical Stack
- **Language**: Kotlin
- **Database**: Room (SQLite)
- **Architecture**: MVVM
- **UI**: Material Design Components
- **Async Operations**: Coroutines
- **View Binding**: Enabled

## Build Requirements
- Android Studio Arctic Fox or newer
- JDK 8 or newer
- Android SDK API 21 or higher
- Gradle 7.0.2

## How to Build
1. Open Android Studio
2. Select "Open an existing Android Studio project"
3. Choose the `notes_app` folder
4. Wait for project sync and dependency download
5. Build > Build Bundle(s) / APK(s) > Build APK(s)

## Project Structure
```
app/src/main/java/com/example/notesapp/
├── Note.kt                    # Data model
├── NoteDao.kt                 # Database interface
├── NoteDatabase.kt            # Room database
├── NoteRepository.kt          # Data repository
├── MainActivity.kt            # Main screen
├── AddEditNoteActivity.kt     # Add/Edit screen
├── SplashActivity.kt          # Splash screen
└── NotesAdapter.kt            # RecyclerView adapter
```

## Minimum Requirements
- Android 5.0 (API level 21)
- 50MB storage space
- 1GB RAM

## License
This project is created for educational purposes.

