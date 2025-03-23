# DotBox

> Drop your dotfiles and walk away like a badass.

DotBox is a dotfile deployment tool for Linux users who want fast setup, no bs, and max ricing power.  
Just give it a `.zip` or Git repo URL, and it installs your dotfiles safely, cleanly, and without crying over broken configs.

---

## Features

- Accepts a `.zip` or GitHub repo URL
- Detects and installs `.bashrc`, `.zshrc`, `.config/` dirs, and more
- Smart overwrite: preview changes, backup originals
- Optional symlinking
- Runs included `install.sh` or post-install hooks
- Built-in rices for WM setups (i3, Hyprland, Sway, etc.)
- Terminal-first, but GUI coming soon

---

## Example Usage

```bash
dotbox install https://example.com/my-dotfiles.zip
