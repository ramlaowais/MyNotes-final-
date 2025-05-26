# MyNotes-final-
# MyNotes App

A simple and elegant Flutter application for managing your notes. This app allows you to create, view, edit, delete, search, and sort your notes efficiently with a clean and intuitive user interface.

## Features

* **Create Notes**: Quickly add new notes with a title and content.
* **View Notes**: See all your notes listed in a user-friendly manner.
* **Edit Notes**: Modify existing notes with ease.
* **Delete Notes**: Remove notes you no longer need, with a confirmation dialog.
* **Search Functionality**: Effortlessly find notes by searching through their titles and content.
* **Sort Options**: Sort notes by:
    * Date (Newest First)
    * Date (Oldest First)
    * Title (A-Z)
    * Title (Z-A)
* **Timestamps**: View creation and last updated timestamps for each note.
* **Modern UI**: Clean and appealing user interface with consistent theming, elevated cards, and clear input fields.
* **Local Storage**: Notes are stored locally using `sqflite` for persistence.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* [Flutter SDK](https://flutter.dev/docs/get-started/install) installed.
* An IDE like [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/mynotes-app.git](https://github.com/yourusername/mynotes-app.git)
    cd mynotes-app
    ```
    (Replace `yourusername` with your actual GitHub username and `mynotes-app` with your repository name)

2.  **Get packages:**
    ```bash
    flutter pub get
    ```

3.  **Run the app:**
    ```bash
    flutter run
    ```

## Project Structure

The project follows a standard Flutter application structure:

* `lib/`: Contains the Dart source code for the application.
    * `main.dart`: The entry point of the application.
    * `note_screen.dart`: Handles the display and management of the list of notes, including search and sort functionalities.
    * `note_detail_screen.dart`: Manages the creation, editing, and deletion of individual notes. It also displays note timestamps.
    * `note.dart`: Defines the `Note` data model.
    * `db_helper.dart`: Manages the database operations using `sqflite`.

## Technologies Used

* [Flutter](https://flutter.dev/) - UI toolkit
* [sqflite](https://pub.dev/packages/sqflite) - SQLite plugin for Flutter
