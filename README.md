# Rancher Oracle GPT

## Link to Rancher Oracle GPT

https://chatgpt.com/g/g-RCOxUM3Mc-the-rancher-oracle

## Project Overview

Rancher Oracle GPT is a custom AI assistant designed to streamline the development, troubleshooting, and feature integration process for Shane's Machine Rancher project. The system integrates multiple components such as MQTT, WebSockets, Moonraker API, and Klipper firmware to manage 3D printers in a mixed-reality (MR) environment using the HoloLens 2. Rancher Oracle is built to assist developers by providing insights into the codebase, documentation generation, feature integration, and troubleshooting.

## Purpose

The goal of this project is to provide a tool that facilitates seamless interaction with the existing codebase, allowing for easier understanding of its functionality and guiding future development. Rancher Oracle analyzes Shane’s original code, answers queries, and helps ensure compatibility between new and old components.

## Features

- **Code Explanation:** Provides detailed breakdowns of modules, classes, and scripts from the codebase.
- **Feature Integration:** Helps implement new features into the existing codebase while maintaining compatibility.
- **Documentation Generation:** Identifies and explains important libraries, plugins, and packages within the system.
- **Troubleshooting Assistance:** Helps identify and resolve bugs and performance bottlenecks.

## How to Use Rancher Oracle GPT

1. **Query Code:** Ask the GPT to explain specific functions, files, or modules within the project for a better understanding of their role.
2. **Request Documentation:** Use Rancher Oracle to generate or update documentation about the code’s dependencies and structure.
3. **Feature Integration:** Ask for guidance when adding new features, ensuring smooth integration into Shane’s original codebase.
4. **Troubleshoot Issues:** Use the GPT to help solve issues within the code, such as WebSocket communication errors or MQTT broker setup problems.

## Example Query

**Test Query:**

Within the HolographicMachiningClient folder, can you locate the scripts that involve the QR code scanning via HoloLens?

**Response:**

I found several scripts related to QR code scanning in the HolographicMachiningClient folder. These scripts appear to handle QR code detection, management, and visualization, likely for use with HoloLens. Here are the key files:
- **QRCode.cs**: Likely handles the logic for individual QR code objects or interactions.
- **QRCodesManager.cs**: This script probably manages multiple QR codes and their states.
- **QRCodesSetup.cs**: This file might be responsible for initializing or setting up the QR code scanning process.
- **QRCodesVisualizer.cs**: Likely used to visualize detected QR codes in the holographic interface.
- **Singleton.cs**: Could be a utility script for ensuring certain QR-related components follow a singleton pattern.
- **SpatialGraphNodeTracker.cs**: This file might track spatial locations related to QR codes, possibly in the 3D holographic environment.

Additionally, the package **Microsoft.MixedReality.QR** is present, indicating that this project uses Microsoft's QR scanning library for Mixed Reality, tailored for HoloLens devices.

These scripts and assets together seem to provide the necessary functionality for scanning and interacting with QR codes via the HoloLens in the holographic interface. Let me know if you want a deeper breakdown of any specific script!

## Known Challenges & Limitations

1. **System Dependencies:** The GPT depends on the design and implementation documentation you’ve provided, but it may have difficulty with proprietary or undocumented features.
2. **Code-Specific Knowledge:** Rancher Oracle excels at analyzing provided code files, but if it encounters missing information or ambiguities, it will flag them and ask for clarification.

## Future Improvements

1. **Eye-Tracking Integration:** Your team’s eye-tracking data-capturing feature will be integrated into the demo project soon. Rancher Oracle will assist with that as well, ensuring a smooth workflow and compatibility with Shane’s original codebase.
2. **Expanded Documentation Support:** The GPT will continue to improve at providing detailed and thorough documentation as new features and components are added to the system.

## Aditional Information

I provided the PDF of the research paper to the student who passed the project down to us published. You're welcome to take a look if you're interested in a more in-depth analysis of the project we are currently expanding on.
