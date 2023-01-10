# Setup

### 1. Install [homebrew](https://brew.sh/) 
```console
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 2. Install [kitty](https://sw.kovidgoyal.net/kitty/)
```console
brew install --cask kitty
```

### 3. Install JetBrains Mono Nerd font
```console
brew tap homebrew/cask-fonts
brew install font-jetbrains-mono-nerd-font
```

### 4. Install packages and tools
- tldr
- rgrep
- fd
- fzf
- rustup
- npm

### 4. Install nvim, helix, vscode
```console
brew install neovim 
brew install helix
brew install --cask visual-studio-code
```

### 5. Create basic dirs
```console
mkdir ~/.config
mkdir ~/Repos
```

### 5. Download configs
```console
cd ~/.config
git clone https://github.com/trimonovds/nvim-config nvim
git clone https://github.com/trimonovds/kitty-config kitty
git clone https://github.com/trimonovds/helix-config helix

cd ~/Repos
git clone https://github.com/trimonovds/vscode-config vscode-config
ln -s ~/Repos/vscode-config/keybindings.json  ~/Library/Application\ Support/Code/User/keybindings.json
ln -s ~/Repos/vscode-config/settings.json ~/Library/Application\ Support/Code/User/settings.json
```

### 6. Install and setup Xcode
