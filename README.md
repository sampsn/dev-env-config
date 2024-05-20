# dev-env-config

Config folders for development tools ie. NeoVim, Tmux, Alacritty, etc.

You are going to want to do the following terminal commands to setup a new computer.

```zsh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```zsh
brew install neovim
brew install tmux
brew install yabai
brew install skhd
brew install --cask font-Lekton-nerd-font
```

Then you can clone the repo and move all the folders into your .config file

Then open tmux and do prefix-shift-I

then open neovim and make sure mason and lazy are installing all plugins and lsp servers, etc
