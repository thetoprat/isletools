# Isle App Tools
<img width="1395" height="988" alt="image" src="https://github.com/user-attachments/assets/cd435839-8d78-48e9-9a33-ee85fa0ef7c8" />

[![GitHub Releases](https://img.shields.io/github/downloads/thetoprat/isletools/total.svg?style=flat-square)](https://github.com/thetoprat/isletools/releases/latest)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-blue.svg)](./LICENSE.md)
[![Discord](https://img.shields.io/discord/1125476200144453642?label=Discord&logo=discord&style=flat-square)](https://discord.gg/kzeUVC6DhP)

---

> ⚠️ **Disclaimer**  
> This project is an independent creation and is **not affiliated, associated, authorized, endorsed by, or in any way officially connected with Afterthought LLC, The Isle, or any of its subsidiaries or affiliates**.  
>  
> The use of any trademarks, logos, or copyrighted material is for **educational and informational purposes only** and remains the property of their respective owners.  
>  
> This software is provided **strictly for educational use**, research, and personal exploration. The developer does **not condone misuse**, including circumventing game protections or violating any terms of service. Use at your own risk.

---


## About Isle App Tools

Isle App Tools is a desktop utility designed to enhance your experience with *The Isle* game. It provides powerful features for both players and server administrators, giving you more control and convenience over your game data and server management.

## Features

* **Save Editor:** Securely decrypt, modify, and re-encrypt player save files. Take full control over your character's data directly from your desktop. *Requires an active license for full functionality.*
* **RCON Client:** Remotely send commands to your game server. Manage server settings, send announcements, and monitor player activity from a user-friendly interface.
* **Server Browser:** Using the EOS API to search various servers for The Isle. This is the same system the game itself uses.

## Installation Guide

Follow these steps to download and install Isle App Tools on your system.

### Prerequisites

Before you begin, please ensure your system meets the following requirements:

* **Operating System:** Windows 10 (64-bit) or newer.
* **.NET Framework:** Ensure you have .NET Framework 4.7.2 or newer installed (usually comes with Windows updates).

### Download the Installer

1.  Go to the [**Isle App Tools Releases page on GitHub**](https://github.com/thetoprat/isletools/releases/latest).
2.  Locate the latest release (e.g., `v1.0.0`).
3.  Under the "Assets" section, download the installer file. It will typically be named something like `IsleAppTools Setup 1.0.0.exe` or similar.

### Running the Installer

1.  Once downloaded, **double-click the installer file** (`.exe`) to start the installation process.
2.  The installer is designed to be straightforward and will guide you through the process.
3.  You might see a brief green installation UI, which is normal for this type of installer.
4.  Once installed, the application will usually launch automatically. A shortcut will be created on your desktop and/or in your Start Menu.

### First Launch

* When you launch Isle App Tools for the first time, it might take a moment to initialize.
* You may be prompted to log in or register an account. This is required to activate the Save Editor functionality.
* Ensure your internet connection is stable for initial setup and license validation.

## Usage

* **Navigation:** Use the sidebar to switch between "Homepage", "Save Editor", and "RCON Client" views.
* **Save Editor:** Follow the on-screen prompts to upload, decrypt, edit, and re-encrypt `.sav` files. Remember that Save Editor functionality requires a valid license.
* **RCON Client:** Enter your server's IP, RCON Port, and Password to connect and send commands.
* **Server Brwoser:** View various servers using the same system The Isle uses.

## Automatic Updates

Isle App Tools includes an automatic update mechanism powered by Squirrel.Windows.

* When a new version of the app is released on GitHub, your installed application will **automatically download updates in the background**.
* You will typically be prompted to **restart the application** to apply the new version.
* This ensures you always have the latest features and bug fixes without needing to manually re-download and reinstall the entire app.

## Basic Troubleshooting

* **"App not launching" / "Missing dependencies"**:
    * Ensure your Windows operating system is up-to-date.
    * Temporarily disable your antivirus/firewall to see if it's blocking the installer or app launch, then add an exception for Isle App Tools.
* **"Firebase connection errors" / "License validation issues"**:
    * Verify your internet connection is active and stable.
    * Ensure no firewall is blocking access to `*.googleapis.com` or `*.firebaseapp.com` domains.
* **"Copy/Paste not working"**: Due to security limitations in certain application contexts, copy/paste might only work reliably within designated input fields or editable areas.

## Support & Community

If you encounter any issues, have questions, or would like to connect with other users, please join our Discord server:

* [**Join our Discord Community!**](https://discord.gg/kzeUVC6DhP)

Report bugs to the issue tracker here on Github.

# ⚙️ ~~For Developers~~
~~There is a Command-Line API for developers wishing to automate features from Isle Tools into their systems. **A license key will be necessary for any pay-to-access feature. Obtain one subscribing to the Orion Labs BuyMeACoffee page.**~~

[THIS IS COMING BACK SOON!]

## License

This software is proprietary and all rights are reserved by Orion Labs.

A valid license key is required to access and use certain features of this application (such as the Save Editor).  
By installing or using this software, you agree to the terms set forth in the [LICENSE.md](./LICENSE.md) file.

Unauthorized modification, redistribution, reverse engineering, or the creation of derivative works is strictly prohibited.  
Use of this software without a valid license key, except where explicitly permitted (e.g., trial mode), is a violation of these terms.

---
