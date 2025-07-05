# Hyprland Configuration

A modern, beautiful Hyprland configuration with improved UI and user experience.

## Features

### 🎨 Visual Improvements
- **Modern color scheme**: Purple-blue gradient borders with subtle inactive borders
- **Enhanced transparency**: Subtle window opacity for better visual depth
- **Improved shadows**: Deeper shadows with better positioning
- **Advanced blur effects**: Multi-pass blur with optimizations for performance
- **Smoother animations**: Custom bezier curves for fluid transitions

### 🔧 Functional Enhancements
- **Complete workspace bindings**: All workspaces 1-10 properly mapped
- **Screenshot functionality**: Full screen, selection, and clipboard support
- **Better window management**: Fullscreen, floating, and grouping controls
- **Smart workspace rules**: Workspaces assigned to specific monitors
- **Improved window rules**: Better floating window handling for common applications

### 🖱️ Input Improvements
- **Enhanced touchpad gestures**: 3-finger workspace switching with fine-tuned sensitivity
- **Better mouse handling**: Resize windows by dragging borders and gaps
- **Natural scrolling**: More intuitive touchpad behavior

### 🖼️ Wallpaper Management
- **Flexible paths**: Uses `~/.config/hypr/` instead of hardcoded user paths
- **Multi-monitor support**: Different wallpapers for each monitor

## Key Bindings

### Window Management
- `Super + Q`: Open terminal
- `Super + C`: Close window
- `Super + F`: Toggle fullscreen
- `Super + T`: Toggle floating
- `Super + G`: Toggle group
- `Super + Tab`: Change group active

### Screenshots
- `Print`: Screenshot selection to clipboard
- `Shift + Print`: Screenshot full screen to file
- `Super + Print`: Screenshot selection to file

### Workspaces
- `Super + 1-9/0`: Switch to workspace 1-10
- `Super + Shift + 1-9/0`: Move window to workspace 1-10

## Installation

1. Clone this repository to `~/.config/hypr/`
2. Ensure required dependencies are installed:
   - `grim` (screenshot utility)
   - `slurp` (screen selection)
   - `wl-clipboard` (clipboard support)
   - `waybar` (status bar)
   - `wofi` (application launcher)
3. Restart Hyprland or reload configuration

## Dependencies

- `grim` - Screenshot utility
- `slurp` - Screen area selection
- `wl-clipboard` - Wayland clipboard utilities
- `waybar` - Status bar
- `wofi` - Application launcher
- `hyprpaper` - Wallpaper daemon

## Customization

The configuration is designed to be easily customizable:

- **Colors**: Edit the `col.active_border` and `col.inactive_border` values
- **Animations**: Modify the bezier curves and animation timings
- **Window rules**: Add application-specific rules in the window rules section
- **Wallpapers**: Replace files in the `Wallpapers/` directory

## Monitor Setup

Current configuration supports a 3-monitor setup:
- **DP-1**: 1920x1080@144Hz (left monitor)
- **DP-2**: 2560x1440@300Hz (main monitor)
- **HDMI-A-1**: 1920x1080@60Hz (right monitor, vertical)

Modify the monitor configuration in `hyprland.conf` to match your setup.