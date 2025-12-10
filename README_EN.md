# NoteBetter Studio

English | [日本語](https://github.com/lineside0418/NoteBetter-Studio/README.md)

**NoteBetter Studio** is a standalone web-based tool designed to easily create configuration files for the Minecraft Fabric Mod "**NoteBetter**".
This tool allows you to visually manage instruments, pitch, and volume for block interactions, automatically generating the necessary JSON configuration files.

## ✨ Features
- **Visual Editor**: Intuitive interface with Minecraft block icons.

- **Custom Sound Support**: Supports not only vanilla sounds but also custom user-defined sound events.

- **Resource Pack Helper**: Automatically generates the sounds.json structure required for custom sounds.

- **Dark Mode**: Eye-friendly interface for late-night configuration.

## 🛠️ Usage Guide

1. **Launch**: Go to the [WebSite](https://lineside0418.github.io/NoteBetter-Studio)

2. **Start Project**:

    - Select "New Project" to start from scratch.

    - Select "Import" to load an existing notebetterfabric.json and continue editing.

3. **Add Blocks**:

    - Click the "+" button at the bottom right.

    - Search for and select the block you want to configure (e.g., glass, diamond_block).

    - For modded blocks not in the list, use "+ Add Custom" to manually enter the Block ID.

4. **Configure Sounds**:

    - Click on a block card to select it (multiple selection is supported).

    - Adjust the following settings in the Inspector Panel on the right:

        - Sound Event: The sound to play (e.g., minecraft:block.note_block.harp). Search is available.

        - Pitch: The pitch of the sound (0.5 - 2.0).

        - Volume: The volume of the sound.

        - Custom Sound: Enable this toggle if you are using a custom sound event that requires a Resource Pack.

5. **Export**:

    - Click the "Export" button at the top right.

    - Config: Download or copy the Mod configuration (notebetterfabric.json). Place this in your .minecraft/config/ folder.

    - Resource Pack: If using custom sounds, you can generate and copy the sounds.json content here. Folder structure instructions are also provided.

## 💻 Requirements

- Modern Web Browsers (Google Chrome, Edge, Firefox, Safari, etc.)

- Internet Connection

- Required for loading block textures from GitHub on first launch. The application logic runs locally.

## ⚠️ Disclaimer

- This is an unofficial community tool.

- Please backup your configurations by downloading them frequently ("Download Config"), as browser cache clearing may remove unsaved data.

Created for NoteBetter Fabric Mod.