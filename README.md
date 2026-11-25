# Klakix Desktop

Klakix Desktop is the free Windows video editor from [Klakix](https://klakix.com). It opens the same editor as [klakix.com](https://klakix.com) (and [aivideoyap.com](https://aivideoyap.com) for Turkish) in its own window, so you can edit on a timeline and create AI videos, images, voiceovers and music with your Klakix account.

- Save exported videos straight to any folder, then "Show in folder"
- Keeps the computer awake while an export is running
- Automatic updates: new versions download in the background and install on restart
- Available in 9 languages; Google sign-in works through your default browser

Your account, projects and credits are the same as on the website. The app itself is free to download. AI generations use your Klakix account credits. On macOS and Linux, use the editor in your browser.

## Download

| | |
|---|---|
| Latest version | [v0.3.0](https://github.com/klakix-ai/klakix-desktop/releases/tag/v0.3.0) |
| Installer | [Klakix-Setup-x64.exe](https://github.com/klakix-ai/klakix-desktop/releases/download/v0.3.0/Klakix-Setup-x64.exe) (114,555,109 bytes) |
| SHA-256 | `d022ae47696faec85ff2c46b6bfeae5526eaae021dd557446640cec24e1f409a` |
| Always the newest | [releases/latest/download/Klakix-Setup-x64.exe](https://github.com/klakix-ai/klakix-desktop/releases/latest/download/Klakix-Setup-x64.exe) |
| All releases | [Releases](https://github.com/klakix-ai/klakix-desktop/releases) |

Check the download in PowerShell:

```powershell
Get-FileHash .\Klakix-Setup-x64.exe -Algorithm SHA256
```

## System requirements

- Windows 10 or Windows 11, 64-bit (x64). Windows on ARM runs it through x64 emulation.
- An internet connection and a Klakix account (sign-up is free; the editor and AI generations run through klakix.com).
- No administrator rights needed: the installer installs for the current user only.

## Code signing and the SmartScreen warning

The installer is **not code-signed yet**. When you run a freshly downloaded copy, Windows SmartScreen may show "Windows protected your PC" and name the publisher as unknown. To continue:

1. Click **More info**.
2. Click **Run anyway**.

Before you do, compare the SHA-256 above with your download. If the hash does not match, do not run the file. The file in this repository's releases is the only official download; the same installer is linked from [klakix.com/desktop-app](https://klakix.com/desktop-app).

## License and privacy

This repository hosts release builds only; there is no source code here and no open-source license is granted for the app. Use of Klakix is subject to the [Terms of Service](https://klakix.com/terms). How data is handled is described in the [Privacy Policy](https://klakix.com/privacy).

The Klakix MCP server and the Blender add-on are open source: [klakix-mcp](https://github.com/klakix-ai/klakix-mcp), [klakix-blender](https://github.com/klakix-ai/klakix-blender).

## Support

[support@klakix.com](mailto:support@klakix.com)
