# Portal for Omarchy

A dark theme for Omarchy using a high-contrast orange and blue duotone palette, inspired by the Portal video game series. 

![Portal desktop preview](preview.jpg)

## Features

- **Duotone Palette:** Standard terminal syntax colors are re-mapped to emphasize orange and blue.
- **Custom Backgrounds:** Includes 15 cycling backgrounds.
- **System Icons:** Configured to use the `Yaru-blue-dark` icon theme.
- **Dark Background:** Uses a `#1a1e24` background color.

## Install

Open the Omarchy Menu with `Super + Space`, then choose **Install > Style > Theme** and paste:

```text
https://github.com/<your-username>/portal
```

Or install from the terminal:

```bash
omarchy theme install https://github.com/<your-username>/portal
```

The theme applies immediately. To return to it later, use **Style > Theme** or press `Super + Ctrl + Shift + Space`.

## Included Integrations

Portal uses Omarchy's `colors.toml` to automatically generate configurations for the following systems:

| Surface | Integrations |
|---|---|
| Omarchy shell | Top bar, menus, launcher, notifications, OSD, auth prompts, image picker, lock screen |
| Hyprland | Borders, rounded corners, gaps, blur, animations, active-window glow |
| Terminals | Ghostty, Alacritty, Kitty, Foot, tmux |
| Editors | Neovim, Helix, Obsidian, VS Code, VSCodium, Cursor |
| CLI Tools | Claude Code, Pi, OpenCode, Gum, btop |
| Browsers | Chromium, Chrome, Edge, Brave, Firefox |
