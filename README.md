# N.O.A. Black

A pure black VS Code theme with purple and red syntax highlighting.

- UI: pure black (`#000000`) everywhere; popups `#050505`-`#0d0d0d` with `#212121` borders.
- Accent: purple `#c678dd` (active tab, panel and activity bar indicators, buttons).
- Syntax (from Zed's One Dark Pro Max):

| Element | Color |
| --- | --- |
| Keywords, storage | `#c678dd` |
| Variables, parameters, properties, tags | `#E15687` |
| Functions, methods | `#61afef` |
| Types, structs, classes | `#e5c07b` |
| Strings | `#98c379` |
| Numbers, constants | `#d19a66` |
| Enums, escapes | `#56b6c2` |
| Comments | `#7F838C` |

## Build and install

Requires Node.js.

```bash
npx --yes @vscode/vsce package --allow-missing-repository
```

```bash
code --install-extension noa-black-theme-1.0.0.vsix
```

Then pick **N.O.A. Black** with `Ctrl+K` `Ctrl+T`.

## Credits

Based on [One Dark Pro](https://github.com/Binaryify/OneDark-Pro) "Night Flat" by Binaryify (MIT).
