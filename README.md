## ovflowd's personal dotfiles

This repository includes ovflowd's personal dotfiles.

In order to install, simply open your bash or zsh and run `./install.sh`. Have fun!

### Before starting

- **ZSH**. We use ZSH. Remember to install ZSH before, or `chsh -s /bin/zsh`
- The `install.script` is compatible with Fedora, Debian and MacOS
- This script will overwrite existing Bash Profile, ZSH and Oh-My-ZSH environments.
- **DO NOT** run the script as **sudo/sudoer** the script will ask for privileges when it needs to.
- The script can be fully executed in an unattended fashion depending of the environment (Docker/CodeSpace/CI pipelines)

#### Note for VS/GitHub CodeSpace Users

- Please install the [Hack Nerd Font](https://github.com/source-foundry/Hack) on your system. This is required for PowerLevel10K. Otherwise Terminal will have broken icons.
- Don't forget to change the font on `Settings > Features > Terminal > Integrated: Font Family` to `'Hack Nerd Font'`.

## Contents

### Reference for Packages

- [Homebrew for Linux](https://brew.sh)
- [Oh-My-ZSH](https://github.com/ohmyzsh/ohmyzsh)
- [Power Level 10K](https://github.com/romkatv/powerlevel10k)
- [Glances](https://github.com/nicolargo/glances)
- [Bat](https://github.com/sharkdp/bat)
- [The Fuck](https://github.com/nvbn/thefuck)
- [McFly](https://github.com/cantino/mcfly)
- [ZSH-Z](https://github.com/agkozak/zsh-z)
- [ZSH Auto Suggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [ZSH Syntax Highlighting](https://github.com/zsh-users/zsh-syntax-highlighting)
- [ZSH History DB](https://github.com/larkery/zsh-histdb)
- [Hack Nerd Font](https://github.com/source-foundry/Hack)
- [Git LFS](https://git-lfs.github.com/)
- [Motivate](https://github.com/mubaris/motivate)

### Included Homebrew Packages

- gcc
- git-lfs
- nmap
- gnupg
- mcfly
- glances
- bat
- htop
- the-fuck
- gh
- coreutils
- sqlite
- figlet
- nvm
- python
- less

### Included ZSH Plugins

- zsh-z
- zsh-autosuggestions
- zsh-syntax-highlithing
- zsh-sqlite-history-completion
- zsh-histdb

### Included System Packages

#### Debian/Ubuntu

- build-essentials
- debconf
- locales
- fonts-hack-ttf
- git

#### Fedora/RedHat/CentOS

- @development-tools
- git
- hack-fonts

#### macOS

- No requirement needs to be installed
- Fonts need to be installed manually. Follow [this](https://github.com/source-foundry/Hack#macos)

#### Windows

- Not compatible yet