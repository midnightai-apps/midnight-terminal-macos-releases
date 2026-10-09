# Midnight Terminal for macOS and Windows

A free SSH terminal and SFTP client for macOS and Windows.

[Download the latest release](https://github.com/midnightai-apps/midnight-terminal-macos-releases/releases/latest)

## Install

### macOS (Apple Silicon)

[Download the macOS DMG](https://github.com/midnightai-apps/midnight-terminal-macos-releases/releases/download/v0.1.102/Midnight-Terminal-0.1.102-mac-arm64.dmg)

1. Download **Midnight-Terminal-0.1.102-mac-arm64.dmg** from Releases.
2. Open the DMG and drag **MidnightAI Terminal.app** into **Applications**.
3. Open **Midnight Terminal** from Applications. Quit any running copy before replacing it.

Requires an **Apple Silicon Mac (M1 or later)** running **macOS 12 or later**. Intel Macs are not supported by this release. The app and DMG are Developer ID signed and notarized by Apple.

### Windows (x64)

- [Download the Windows installer](https://github.com/midnightai-apps/midnight-terminal-macos-releases/releases/download/v0.1.102/Midnight-Terminal-0.1.102-win-x64-setup.exe)
- [Download the Windows ZIP](https://github.com/midnightai-apps/midnight-terminal-macos-releases/releases/download/v0.1.102/Midnight-Terminal-0.1.102-win-x64.zip)

Requires **Windows 10/11 (64-bit)**. Run the installer, or extract the ZIP and open **Midnight Terminal.exe**. Local terminals support CMD and Windows PowerShell, plus PowerShell 7 when installed.

The Windows installer is **not code signed**. Windows may show an unknown publisher warning or block execution depending on SmartScreen or Smart App Control policy. Follow your organization's security policy; a signed Windows installer is not available in this release.

The Windows build passed installation, GUI terminal/tab/settings/restart, loopback SSH/SFTP and uninstall QA in Windows Sandbox. Windows updates use this same release repository and its latest.yml manifest.

## Free to use

No payment, account, subscription, trial period, activation or license key is required.

- SSH terminal tabs and SFTP file transfers
- Local zsh/bash terminals on macOS, with no separate helper installation for this DMG edition; CMD/PowerShell terminals on Windows
- Saved hosts and commands
- SSH Local, Remote and SOCKS port forwarding
- Terminal themes, font selection, and English/Korean interface
- In-app updates from this public release repository

Third-party notices are available inside the app under **Help > Open Source Licenses**. “Free to use” does not change third-party license obligations or make the application source public.

This repository contains release downloads and documentation only. Application source is maintained separately. GitHub's automatically generated source archives for this repository contain its documentation, not the application source.

[Privacy Policy](https://www.midnightai.net/html/terminal/privacy-policy.html)

For updates, use the app's update command or install the latest DMG (macOS) or installer (Windows). Direct-edition settings retain their existing profile; the App Store/TestFlight edition has a separate sandbox profile.
