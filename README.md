# Doom One Theme for VS Code

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/lroolle.doom-themes?style=flat-square&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=lroolle.doom-themes)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/lroolle.doom-themes?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=lroolle.doom-themes)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

Faithful port of **Doom Emacs doom-one theme** to VS Code. Dark and light variants with complete UI theming.

## Installation

### From VS Code Marketplace
[**Install from Marketplace**](https://marketplace.visualstudio.com/items?itemName=lroolle.doom-themes) or:

**Extensions** → Search "Doom Themes" → **Install** → **Command Palette** (`Ctrl+Shift+P`) → "Color Theme" → Select **Doom One Dark** or **Doom One Light**

### Quick Install
Launch VS Code Quick Open (`Ctrl+P`), paste the following command, and press enter:
```
ext install lroolle.doom-themes
```

## Themes

**Doom One Dark** - `#282c34` background, vibrant syntax highlighting  
**Doom One Light** - `#fafafa` background, clean and minimal

## Colors

| Element | Dark | Light |
|---------|------|-------|
| Background | `#282c34` | `#fafafa` |
| Keywords | `#51afef` | `#e45649` |
| Strings | `#98be65` | `#50a14f` |
| Functions | `#c678dd` | `#a626a4` |
| Types | `#ECBE7B` | `#986801` |

## Development

### Automated Publishing

This extension uses GitHub Actions for automated publishing:

- **On tag creation** (`v*`): Automatically publishes to VS Code Marketplace
- **On PR/push**: Packages and tests the extension
- **Manual trigger**: Can be run manually from GitHub Actions tab

### Local Development

```bash
# Package the extension locally
npm run package

# Publish manually (with version bump)
npm run publish:patch   # 1.0.0 → 1.0.1
npm run publish:minor   # 1.0.0 → 1.1.0  
npm run publish:major   # 1.0.0 → 2.0.0
```

## Credits

Original: [Doom Emacs](https://github.com/doomemacs/doomemacs) by Henrik Lissner  
License: MIT
