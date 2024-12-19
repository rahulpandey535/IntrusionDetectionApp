# Intrusion Detection and Prevention App

## Overview
The Intrusion Detection and Prevention App is a cybersecurity application for iOS devices that monitors suspicious activity and alerts users in real-time. Using Apple's Network Framework and CoreML, this app analyzes network traffic, detects potential threats, and notifies the user to take immediate action.

---

## Features
- **Real-Time Threat Detection**: Monitors network traffic and identifies potential threats such as DoS attacks or phishing attempts.
- **Machine Learning Integration**: Uses CoreML to detect abnormal behavior patterns.
- **User Notifications**: Alerts users about threats via local notifications.
- **Secure Reporting**: Tracks suspicious IPs and provides real-time insights into network activities.
- **User-Friendly Interface**: Simple and intuitive UI built with SwiftUI.

---

## Requirements
- Xcode 15 or later
- iOS 17.0 or later
- Swift 5.9 or later

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rahulpandey02124/IntrusionDetectionApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd IntrusionDetectionApp
   ```
3. Open the Xcode project:
   ```bash
   open IntrusionDetectionApp.xcodeproj
   ```
4. Build and run the project on an iOS simulator or device.

---

## Project Structure
- **`ContentView.swift`**: Contains the main UI logic for the app, including real-time threat alerts.
- **`NetworkMonitor.swift`**: Monitors network connectivity using Apple's Network Framework.
- **`NotificationManager.swift`**: Manages user notifications, including permission requests and sending alerts.
- **`AppDelegate.swift` / `SceneDelegate.swift`**: Handles app lifecycle events and initializes required managers.

---

## How It Works
1. **Network Monitoring**: The `NetworkMonitor` class continuously checks the device's network connectivity and reports status changes.
2. **Intrusion Detection**: CoreML models analyze network traffic and detect anomalies.
3. **Notifications**: The `NotificationManager` sends local alerts when threats are detected, ensuring users are informed in real-time.

---

## Usage
1. Launch the app on your device.
2. Grant notification permissions when prompted.
3. Tap the "Start Monitoring" button to begin monitoring network activities.
4. Receive alerts for any suspicious activity detected by the app.

---

## Future Enhancements
- **VPN Integration**: Add secure VPN capabilities for enhanced protection.
- **Threat Mitigation**: Automatically block suspicious IPs and prevent unauthorized access.
- **Cloud Integration**: Sync logs and reports to a secure cloud service.

---

## Contact
**Author**: Rahul Pandey  
**Email**: [rahulpandey02124@gmail.com](mailto:rahulpandey02124@gmail.com)  

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

