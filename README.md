# Zed Editor Settings Repository

This repository contains my personal settings, configuration files, and customizations for the Zed code editor. This centralized approach allows for easy synchronization across different machines and provides a backup of my preferred editor setup.

## What's Included

- `settings.json`: Core editor preferences and configurations
- `keymap.json`: Custom keyboard shortcuts and keybindings
- `themes/`: Custom color themes and visual customizations
- `extensions/`: Configuration for installed extensions
- `snippets/`: Code snippets for various languages

## Setup Instructions

### Quick Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/username/zed-settings.git
   ```

2. Create a symbolic link to your Zed configuration directory:

   **macOS/Linux:**
   ```bash
   ln -sf "$(pwd)/zed-settings" ~/.config/zed
   ```

   **Windows:**
   ```powershell
   New-Item -ItemType SymbolicLink -Path "$env:APPDATA\Zed" -Target "path\to\zed-settings"
   ```

3. Restart Zed editor to apply changes

### Manual Setup

If you prefer to selectively apply settings:

1. Open Zed editor
2. Access settings with `Cmd+,` (macOS) or `Ctrl+,` (Windows/Linux)
3. Copy the content from the corresponding files in this repository
4. Paste into your settings interface
