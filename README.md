# 🔒 Password Manager - Tkinter App

A simple desktop application built with **Python and Tkinter** to securely store and manage your website login credentials. It features a password generator and the ability to save and retrieve login details.

---

## 🧩 Features

-   **Password Generation:** Generates strong, random passwords with a mix of letters, numbers, and symbols.
-   **Save Credentials:** Allows you to save website, email/username, and the generated or manually entered password.
-   **Search Functionality:** Easily retrieve saved email and password details for a specific website.
-   **Clipboard Integration:** Automatically copies generated passwords to your clipboard for convenience.
-   **Persistent Storage:** Stores your data in a `data.json` file, ensuring your passwords are saved across sessions.
-   **User-Friendly Interface:** Clean and intuitive GUI built with Tkinter.

---
---

## 📁 File Structure

.
├── main.py             # Main Python script for the Password Manager application
├── data.json           # (Automatically created) Stores saved password data
└── logo.png            # Application logo (required for the GUI)
└── README.md           # Project documentation


---

## 🛠️ How to Run

To run this application, you'll need Python 3 installed on your system.

### Prerequisites

-   Python 3.x
-   `tkinter` (usually comes pre-installed with Python)
-   `pyperclip` (for copying passwords to clipboard)

### Installation

1.  **Clone or download** this repository to your local machine.
2.  **Navigate** into the project directory:
    ```bash
    cd your_project_folder
    ```
3.  **Install the `pyperclip` library** if you don't have it:
    ```bash
    pip install pyperclip
    ```
4.  **Place `logo.png`:** Ensure you have an image file named `logo.png` in the same directory as `main.py`. This image will be used as the application's logo in the GUI. You can use any 200x200 pixel image.

### Running the Application

1.  From the project directory, run the Python script:
    ```bash
    python main.py
    ```
2.  The Password Manager application window will appear.

---

## 🎮 Usage

1.  **Enter Website:** Type the name of the website (e.g., "Google", "Facebook") into the "Website" field.
2.  **Enter Email/Username:** Type your email or username for that website into the "Email/Username" field. (It's pre-filled with a placeholder, you can change it).
3.  **Generate Password:** Click the "Generate Password" button to automatically create a strong, random password. This password will be inserted into the "Password" field and copied to your clipboard.
4.  **Add/Save:** Click the "Add" button to save the website, email, and password. A confirmation dialog will appear before saving. The data will be stored in `data.json`.
5.  **Search Password:** To retrieve a saved password, enter the website name in the "Website" field and click the "Search" button. If found, a message box will display the saved email and password. If not, an error message will appear.

---

## 🚀 Ideas for Improvement

-   **Encryption:** Implement encryption for the `data.json` file to enhance security.
-   **Master Password:** Add a master password to unlock the application.
-   **UI Enhancements:** Improve the visual design and layout.
-   **Password Strength Indicator:** Provide feedback on the strength of manually entered passwords.
-   **Delete/Edit Entries:** Add functionality to delete or modify existing saved entries.
-   **Categorization:** Allow users to categorize passwords (e.g., social, banking).
-   **Cross-platform compatibility:** Consider using frameworks like PyQt or Kivy for broader platform support if needed.

---

## 📜 License

This project is for educational purposes. Feel free to modify and improve it!
