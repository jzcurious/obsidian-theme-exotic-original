# Exotic Theme for Obsidian

A unique and visually striking theme for [Obsidian](https://obsidian.md/) that brings an exotic atmosphere to your note-taking experience. Designed with attention to detail and aesthetics, this theme enhances readability and visual appeal while maintaining focus on your thoughts.

## ✨ Features

- **Monospace Typography**: Entirely styled with "Source Code Pro" for both editor and preview.
- **Glassmorphism UI**: Semi-transparent modals, menus, and prompts with blur and brightness effects.
- **Customizable Colors**: All colors are defined as CSS variables for easy personalization.
- **Enhanced Tables**: Alternating row colors and hover effects for better readability.
- **Inline & Block Code Styling**: Distinct visual treatment for code snippets and blocks.
- **Smooth Transitions**: Hover animations for buttons, tables, and other interactive elements.
- **Dark-Optimized Design**: Carefully chosen contrast for long reading sessions.

## 🖼️ Screenshots

![Screenshot 1 - Editor Mode](screenshots/editor.png)
*Editor mode with syntax highlighting*

![Screenshot 2 - Preview Mode](screenshots/preview.png)
*Preview mode showcasing typography and styling*

![Screenshot 3 - Graph View](screenshots/graph.png)
*Graph view with custom node fonts*

## 🛠️ Installation

### Manual Installation

1. Download the latest release from the [Releases](https://github.com/jzcurious/obsidian-theme-exotic-original.git) page.
2. Extract the files into your vault’s themes folder: `<vault>/.obsidian/themes/Exotic/`
3. Open Obsidian Settings → Appearance → Themes.
4. Select “Exotic” from the dropdown menu.
5. Reload Obsidian or restart if prompted.

## 🎨 Customization

All colors and effects are defined via CSS variables in the `:root` section of the theme. You can easily modify them by editing the `theme.css` file:

```css
:root {
  --default-font: "Source Code Pro", monospace;
  --brightness: 0.54;
  --blur: 100px;
  --color-theme-accent: #aef93eee;
  --color-header: #6666fff0;
  --color-italic: #99d542f6;
  --color-inline-code: #ebae14;
  --color-code-inline-bg: #4c4c4cb0;
  --color-code-block-bg: rgba(77, 77, 77, 0.25);
  --color-table-header-bg: #99d54277;
  --color-table-odd-bg: rgba(77, 77, 77, 0.25);
  --color-table-even-bg: rgba(128, 255, 255, 0.25);
  --color-handles-bg: #aef93e77;
  --color-handles-active-bg: var(--color-theme-accent);
}
```

### Key Variables

- `--brightness` / `--blur`: Control backdrop filter intensity.
- `--color-theme-accent`: Primary accent color used across UI elements.
- `--color-header`: Color for headings.
- `--color-italic`: Color for emphasized (italic) text.
- `--color-inline-code`: Color for inline code.
- `--color-code-block-bg`: Background for code blocks.

## 🧩 Compatibility

- Works best with Obsidian v1.10.6+
- Compatible with most core plugins
- May require adjustments with heavy UI customization plugins

## 🤝 Contributing

Feel free to open issues for bugs or suggestions. Pull requests are welcome!

## 📜 License

MIT License. See [LICENSE](./LICENSE) for more details.

## 👨‍💻 Author

**jzcurious**
[GitHub Profile](https://github.com/jzcurious)
