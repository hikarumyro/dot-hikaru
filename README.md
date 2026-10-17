# My Hyprland Dotfiles

Personal desktop configuration for EndeavourOS / Arch Linux with Hyprland.

## Included

- Hyprland and Hyprlock
- Walker with Forest and Macchiato themes
- Waybar
- Kitty with Catppuccin Macchiato
- Mako notifications
- Wofi styling
- Screenshot script

## Requirements

See `packages.txt` for the initial package list.

Some commands and dependencies may need to be installed separately.

## Installation

1. Back up your existing configuration files.
2. Install the required packages.
3. Copy the desired directories into `~/.config/`.
4. Copy `scripts/screenshot` to `~/.local/bin/screenshot`.
5. Make the script executable:

   `chmod +x ~/.local/bin/screenshot`

6. Review `hypr/hyprland.conf` before starting Hyprland.

## Important

- Review monitor settings for your own displays.
- Update the wallpaper path in `hyprland.conf` and `hyprlock.conf`.
- Make sure the wallpaper exists in `~/Pictures/Wallpapers/`.
- Check startup commands and install any missing dependencies.
- Do not overwrite your existing configuration without a backup.
