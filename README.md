# Dependancies
| App              | Package         |
|------------------|-----------------|
| Shell            | zsh             |
| Window Manager   | hyprland        |
| Status Bar       | waybar          |
| Terminal         | kitty           |
| Editor           | vs code         |

# Install
archinstall with hyprland desktop profile

## Install Packages

```
yay -Syu zsh \
    waybar-hyprland \
    swaylock-effects \
    wlogout \
    mako \
    hyprpaper \
    ttf-jetbrains-mono-nerd \
    nwg-look \
    dracula-gtk-theme \
    dracula-icons-git \
    pavucontrol \
    grim \
    slurp \
    google-chrome \
    spotify-launcher \
    python-gobject \
    visual-studio-code-bin \
```

## Get config files

```
git clone --depth 1 --separate-git-dir=$HOME/.dotfiles https://github.com/martinbartolo/dotfiles.git $HOME/dotfiles-tmp
    rm -r ~/dotfiles-tmp/
    alias config='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
```
