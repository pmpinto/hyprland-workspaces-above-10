# Hyprland Workspaces Beyond 10
A submap-based solution for using unlimited workspaces in Hyprland without being limited to the number row on your keyboard.

## The Problem
Hyprland supports unlimited workspaces, but the default setup limits you to 10 (bound to keys 0-9). What about workspace 20? 88? 99?

## The Solution
- `SUPER + ALT + EQUAL` → type any number to *go* to that workspace
- `SUPER + ALT + SHIFT + EQUAL` → type any number to *move* the active window there

## How It Works
1. Press the keybind to enter "workspace mode"
2. Type a number (e.g., "88")
3. Press Enter → you're now in workspace 88

## Installation
1. Copy the `system-workspaces-10-plus` script
2. Make it available in your `$PATH`
3. Add the bindings from `bindings.conf` to your Hypr config
