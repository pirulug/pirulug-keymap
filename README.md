# Pirulug Keymap for VS Code

[![Version](https://img.shields.io/visual-studio-marketplace/v/pirulug.pirulug-keymap?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-keymap)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/pirulug.pirulug-keymap?style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=pirulug.pirulug-keymap)
[![License](https://img.shields.io/github/license/pirulug/pirulug-keymap?style=for-the-badge)](LICENSE)

Elevate your productivity with the **Pirulug Keymap**, a curated set of keyboard shortcuts designed for speed, efficiency, and comfort in Visual Studio Code.

<p align="center">
  <img src="pirulug-keyboard.png" alt="Pirulug Keymap Logo" width="200">
</p>

## Key Features

- **Intuitive Editing**: Quick access to comments, formatting, and line manipulations.
- **Seamless Navigation**: Smooth scrolling, quick symbol lookup, and editor switching.
- **Efficient Searching**: Find and replace actions optimized for speed.
- **Multi-Platform Support**: Works seamlessly on Windows and macOS.

## Shortcuts Reference

### Editing & Formatting
| Action | Keybinding (Win/Linux) | Keybinding (Mac) |
| :--- | :--- | :--- |
| **Add Line Comment** | `Ctrl` + `Numpad /` | `Ctrl` + `Numpad /` |
| **Block Comment** | `Ctrl` + `Alt` + `Numpad /` | `Ctrl` + `Alt` + `Numpad /` |
| **Block Comment (Alt)** | `Ctrl` + `Shift` + `/` | `Alt` + `Cmd` + `/` |
| **Format Document** | `Ctrl` + `Alt` + `F` | `Ctrl` + `Alt` + `F` |
| **Remove Line Comment** | `Ctrl` + `Numpad *` | `Ctrl` + `Numpad *` |
| **Copy Lines Down** | `Ctrl` + `D` | `Cmd` + `D` |
| **Delete Lines** | `Shift` + `Cmd` + `D` | `Shift` + `Cmd` + `D` |
| **Move Lines Up** | `Ctrl` + `Shift` + `Up` | `Cmd` + `Ctrl` + `Up` |
| **Move Lines Down** | `Ctrl` + `Shift` + `Down` | `Cmd` + `Ctrl` + `Down` |

### Navigation
| Action | Keybinding (Win/Linux) | Keybinding (Mac) |
| :--- | :--- | :--- |
| **Scroll Line Up** | `Ctrl` + `Up` | `Alt` + `Ctrl` + `Up` |
| **Scroll Line Down** | `Ctrl` + `Down` | `Alt` + `Ctrl` + `Down` |
| **Go to Line** | `Ctrl` + `G` | `Cmd` + `G` |
| **Go to Symbol** | `Ctrl` + `T` | `Cmd` + `T` |
| **Show All Symbols** | `Ctrl` + `Shift` + `T` | `Cmd` + `Shift` + `T` |
| **Reveal Definition** | `Ctrl` + `J` | `Cmd` + `J` |
| **Next Error/Warning** | `F8` | `Cmd` + `'` |
| **Next Editor** | `Ctrl` + `PageDown` | `Ctrl` + `PageDown` |
| **Previous Editor** | `Ctrl` + `PageUp` | `Ctrl` + `PageUp` |
| **Rename Symbol** | `Ctrl` + `Alt` + `R` | `Alt` + `Cmd` + `R` |
| **Quick Fix** | `Ctrl` + `Alt` + `Enter` | `Alt` + `Cmd` + `Enter` |

### Search & Selection
| Action | Keybinding (Win/Linux) | Keybinding (Mac) |
| :--- | :--- | :--- |
| **Replace** | `Ctrl` + `H` | `Alt` + `Cmd` + `F` |
| **Replace (Alt)** | `Ctrl` + `Shift` + `H` | `Alt` + `Cmd` + `Shift` + `F` |
| **Select All Matches** | `Alt` + `F3` | `Cmd` + `Ctrl` + `G` |
| **Quick Open** | `Ctrl` + `Shift` + `O` | `Ctrl` + `Shift` + `O` |
| **Expand Selection** | `Ctrl` + `L` | `Ctrl` + `L` |
| **Column Select Up** | `Shift` + `Alt` + `Up` | `Shift` + `Alt` + `Up` |
| **Column Select Down** | `Shift` + `Alt` + `Down` | `Shift` + `Alt` + `Down` |

### Workspace & File Management
| Action | Keybinding (Win/Linux) | Keybinding (Mac) |
| :--- | :--- | :--- |
| **Save All** | `Ctrl` + `Alt` + `S` | `Ctrl` + `Alt` + `S` |
| **Open File/Folder** | `Ctrl` + `Alt` + `O` | `Alt` + `Cmd` + `O` |
| **Close All Editors** | `Ctrl` + `Shift` + `W` | `Shift` + `Cmd` + `W` |
| **Toggle Sidebar** | `Ctrl` + `Alt` + `H` | `Cmd` + `Shift` + `H` |
| **Focus Next Pane** | `Ctrl` + `Alt` + `Right` | `Alt` + `Cmd` + `Right` |
| **Focus Previous Pane**| `Ctrl` + `Alt` + `Left` | `Alt` + `Cmd` + `Left` |
| **Move Tab Left** | `Ctrl` + `Alt` + `PageUp`| `Alt` + `Cmd` + `PageUp` |
| **Move Tab Right** | `Ctrl` + `Alt` + `PageDown`| `Alt` + `Cmd` + `PageDown` |

### Extensions
| Action | Keybinding (Win/Linux) | Keybinding (Mac) |
| :--- | :--- | :--- |
| **Live Server: Go Online**| `Ctrl` + `Alt` + `P` | `Alt` + `Cmd` + `P` |
| **Toggle Terminal** | `Ctrl` + `Alt` + `T` | `Alt` + `Cmd` + `T` |

## Installation

1. Open **Visual Studio Code**.
2. Go to the **Extensions** view (`Ctrl+Shift+X`).
3. Search for **Pirulug Keymap**.
4. Click **Install**.

## Development

If you want to contribute or build the theme from source:

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Generate the theme JSON files from the source files in `src/`:
   ```bash
   npm run build
   ```
4. Package the extension into a `.vsix` file:
   ```bash
   # Install vsce first if you haven't: npm install -g @vscode/vsce
   vsce package

## Contributing

If you have suggestions for new keybindings or enhancements, feel free to open an issue or submit a pull request on our [GitHub repository](https://github.com/pirulug/pirulug-keymap).

---

**Developed by [Pirulug](https://github.com/pirulug)**
