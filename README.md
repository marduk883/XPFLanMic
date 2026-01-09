# XPFLanMic
A web-app tool to use any device on the same LAN as a wireless microphone for your PC.

Use any device (mobile, tablet, or another PC) on your local network as a wireless microphone for your computer.

## Option 1: Quick Installation
**Note:** Since the installer is not digitally signed, Windows Defender or SmartScreen may block it. You might need to temporarily disable your Firewall/Antivirus or click "Run anyway" during installation.
1. Download `LanMic_Setup.exe`.
2. Run the installer as Administrator.
3. Follow the instructions to install the VB-CABLE Driver (included).
4. Restart your computer (Required for the driver to work).
5. Launch LanMic Share from your desktop shortcut.

## Option 2: Manual Installation
If you want to run the project from source, follow these steps:

### Prerequisites
1. Python 3.11+
2. VB-CABLE Driver: https://vb-audio.com/Cable/
3. After installing VB-CABLE Driver and Python, restart your PC.

### Installation Steps
1. Download `XPFLanMic.zip` and extract it to a folder.
2. Open CMD or Terminal inside the extracted folder.
3. Install the required libraries via CMD ; pip install flask flask-socketio sounddevice numpy eventlet cryptography
4. Run XPFLanMic/app.py
5. Enjoy
