# Cyberpunk 2077 - VS Code Theme

A dark theme for Visual Studio Code inspired by the Cyberpunk 2077 universe. Neon colors on a dark background bring the Night City aesthetic to your editor.

## Color Palette

| Color Name      | Hex       | Usage                         |
| --------------- | --------- | ----------------------------- |
| Raisin Black    | `#272932` | Editor background             |
| Blood Red       | `#710000` | Errors, invalid code          |
| Rich Lemon      | `#FDF500` | Strings, CSS classes          |
| Keppel          | `#1AC5B0` | Operators, punctuation, types |
| Electric Blue   | `#37EBF3` | Functions, methods, cursor    |
| Blushing Purple | `#9370DB` | Keywords, storage, attributes |
| Frostbite       | `#E455AE` | Numbers, constants, variables |
| Steel Pink      | `#CB1DCD` | Tags, badges, buttons         |
| White           | `#FFFFFF` | Default text                  |

## Installation

### From source

1. Copy the folder to your VS Code extensions directory:

```
# Windows
copy "cyberpunk-2077" to %USERPROFILE%\.vscode\extensions\cyberpunk-2077

# macOS / Linux
cp -r cyberpunk-2077 ~/.vscode/extensions/cyberpunk-2077
```

2. Restart VS Code.
3. Open the Command Palette (`Ctrl+K Ctrl+T`) and select **Cyberpunk 2077**.

### From VSIX

1. Install the packaging tool: `npm install -g @vscode/vsce`
2. Run `vsce package` in the project root.
3. In VS Code, open Command Palette (`Ctrl+Shift+P`) and run **Extensions: Install from VSIX...**, then select the generated `.vsix` file.

## Features

- Full UI theming: editor, sidebar, activity bar, tabs, status bar, terminal, buttons, inputs, scrollbar, breadcrumbs, panels, peek view, minimap
- Syntax highlighting for all major languages
- Git decoration colors
- JSON key coloring by nesting level
- Markdown styling
- Terminal ANSI color mapping

## Development

1. Open this project in VS Code.
2. Press `F5` to launch the Extension Development Host with the theme loaded.
3. Edit `themes/Cyberpunk 2077-color-theme.json` and save -- changes apply in real time.
4. Use `Developer: Inspect Editor Tokens and Scopes` from the Command Palette to inspect any token's scope and applied color.

## License

MIT
