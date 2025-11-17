# MQTT-NP

<img height="640" alt="изображение" src="https://github.com/user-attachments/assets/3d3c54e9-72ed-4bb8-9736-7b071a7e75da" />



## 📋 Overview

MQTT-NP is a cross-platform desktop MQTT client designed for developers and IoT enthusiasts. Built with modern web technologies and Rust, it provides a fast, secure, and user-friendly interface for monitoring and managing MQTT brokers.

## ✨ Features

### 🔌 Connection Management
- **Multiple Server Profiles** - Save and switch between different MQTT brokers
- **Secure Connections** - Support for authentication (username/password)
- **Connection Status** - Real-time connection monitoring with visual indicators
- **Quick Switch** - Seamlessly switch between servers without losing data

### 📊 Topic Management
- **Dynamic Topic Discovery** - Automatically discover topics from broker
- **Infinity Topics Explorer** - Subscribe to all topics with `#` wildcard
- **Topic Filtering** - Select which topics to monitor
- **Visual Indicators** - Animated notifications when messages arrive
- **Bulk Operations** - Unselect all, remove all, or remove unselected topics

### 📝 Message Logging
- **Real-time Messages** - View incoming messages as they arrive
- **Message Counter** - Track message order with reverse numbering
- **Copy to Clipboard** - Quick copy functionality for message payloads
- **Topic Subscription** - Subscribe to new topics directly from logs
- **Clear Logs** - Clean slate with one click

### 🎨 User Interface
- **Modern Design** - Clean, intuitive interface built with Tailwind CSS
- **Dark Mode** - Easy on the eyes with dark theme support
- **Responsive Layout** - Optimized for desktop and mobile screens
- **Sidebar Navigation** - Quick access to all features
- **Keep-Alive Views** - Maintains state when switching between pages

### ⚙️ Settings
- **Infinity Topics Explorer** - Toggle automatic topic discovery
- **Connection Persistence** - Remembers your last connection
- **Topic Persistence** - Saves topics per connection

## 🚀 Installation

### Download

Download the latest version for your platform from the [Releases](https://github.com/leruetkins/mqtt-np-tauri/releases) page:

- **Windows**: `MQTT-NP.exe`
- **Linux**: `MQTT-NP.elf`

## 📖 Usage

### Quick Start

1. **Add a Connection**
   - Navigate to "Connections" from the sidebar
   - Click "Add Connection"
   - Enter broker details (address, port, credentials)
   - Click "Add Connection"

2. **Select a Server**
   - Click "Select" on your desired connection
   - The app will automatically connect

3. **Monitor Topics**
   - Add topics manually with "Add Topic" button
   - Or enable "Infinity Topics Explorer" in Settings to auto-discover
   - Click on topic badges to toggle subscription
   - Watch messages appear in real-time

4. **Manage Topics**
   - **Unselect All** - Unsubscribe from all active topics
   - **Remove All** - Delete all topics from the list
   - **Remove Unselected** - Clean up inactive topics

## 💡 Tips & Tricks
- **Infinity Explorer** - Enable in Settings to automatically discover all topics from your broker
- **Message Copy** - Hover over any message and click the copy icon to copy the payload
- **Quick Subscribe** - Click on any topic in the message log to subscribe to it
- **Connection Switching** - Your topics and settings are saved per connection

## ❓ FAQ

**Q: Can I connect to multiple brokers simultaneously?**  
A: Currently, you can only connect to one broker at a time, but you can quickly switch between saved connections.

**Q: Does it support MQTT over WebSockets?**  
A: Not yet, but it's planned for a future release.

**Q: Where are my settings stored?**  
A: Settings are stored locally on your device in a secure location managed by Tauri.

**Q: Is my data sent anywhere?**  
A: No, MQTT-NP is a fully offline application. All data stays on your device.


## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? Please open an issue on [GitHub Issues](https://github.com/leruetkins/mqtt-np-tauri/issues).

When reporting a bug, please include:
- Your operating system and version
- MQTT-NP version
- Steps to reproduce the issue
- Expected vs actual behavior

## 📧 Contact

Project Link: [https://github.com/leruetkins/mqtt-np-tauri](https://github.com/leruetkins/mqtt-np-tauri)

---

<div align="center">
Made with ❤️ by the Naben
</div>
