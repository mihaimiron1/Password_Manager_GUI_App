# 🔐 Password Manager GUI App

This is a Python-based desktop application that offers a simple and intuitive graphical interface for generating, saving, and retrieving passwords. The project uses `tkinter` for the GUI and stores data in JSON format.

## 🚀 Features

- ✅ Automatically generates secure passwords (letters, numbers, symbols)
- 💾 Saves passwords and email addresses for each website
- 🔍 Fast search by website name
- 📋 Automatically copies the generated password to the clipboard
- 🔐 Locally stored data in a structured JSON file (`data.json`)

## 🛠️ Technologies Used

- Python 3
- Tkinter – GUI library
- Pyperclip – clipboard operations
- JSON – for saving/loading data locally

## 📁 Project Structure

Password_Manager_GUI_App/

├── data.json # The file where passwords are stored

├── logo.png # Logo image shown in the app

└── main.py # The main script of the application


## ▶️ How to Run

1. Install dependencies:

```bash
pip install pyperclip
```
2. Run the application:
```bash
python main.py
```

⚠️ Note
The data is saved locally in a JSON file. For real-world use, it is recommended to encrypt the file.

The logo.png image must be present in the Password_Manager_GUI_App folder, or the app will fail to load the image.
