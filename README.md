# portable-vscode-usb
Run Visual Studio Code in fully portable mode from a USB drive on Windows, with all settings and extensions stored locally.
# Portable Visual Studio Code on USB (Windows)

This repository explains how to run **Visual Studio Code** in **official portable mode** directly from a USB drive.

✅ No installation required  
✅ No admin permissions  
✅ Extensions and settings stay on USB  
✅ Works on any Windows PC  

---

## 🔧 Requirements

- Windows OS
- USB drive (USB 3.0+ recommended)

---

## 📥 Download VS Code (ZIP Version)

1. Go to the official site:
   https://code.visualstudio.com/download

2. Under **Windows**, select:
   - **User Installer → ZIP (x64)**  
   ⚠️ Do **NOT** download the `.exe` installer.

---

## 📂 Setup Portable Mode

1. Plug in your USB drive  
   - Example: `E:\`

2. Extract the downloaded ZIP directly to USB:
3.  Inside the extracted folder, create:
 
5. Final folder structure:

E:\VSCode
├── Code.exe
├── resources
├── data\


The `data` folder enables **portable mode**.

---

## ▶️ Run VS Code

- Double-click:

All extensions, settings, and user data are stored in:
E:\VSCode\data

---

## 🔌 Extensions

- Install extensions normally
- They remain permanently on the USB

---

## 🔄 Updating VS Code

1. Download the latest ZIP version
2. Extract it over the existing `VSCode` folder
3. **Do not delete the `data` folder**

---

## ⚠️ Notes

- Avoid unplugging the USB while VS Code is running
- First startup may be slower on older USB drives

---

## 📜 License

This repository is documentation only.  
Visual Studio Code is licensed by Microsoft.
