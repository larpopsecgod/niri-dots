# niri-dots

These are my dotfiles for Kitty and Niri for Arch and its derivatives!

These dots will work fine on their own, but you will need to use the Iosevka Nerd Font to get the exact font I have. Otherwise, feel free to edit it using `kitten choose-fonts`.

## Installation

### Dependencies
Ensure you have `niri`, `kitty`, and the `iosevka` nerd font installed via your package manager:
```bash
sudo pacman -S niri kitty ttf-iosevka-nerd
```

### Configuration
Create the target XDG configuration directories and clone/place the files into their appropriate locations:

```bash
# Setup directories
mkdir -p ~/.config/niri ~/.config/kitty

# Move the configuration files to their locations
# (If cloning, copy config.kdl to ~/.config/niri/ and kitty.conf to ~/.config/kitty/)
cp config.kdl ~/.config/niri/config.kdl
cp kitty.conf ~/.config/kitty/kitty.conf
```
