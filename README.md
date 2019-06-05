# Getting started

## Install xfce-terminal theme

cp terminalrc ~/.config/xfce4/terminal/terminalrc 

## Install dircolors

cp .dir_colors ~/.dir_colors

## Zsh

### Install Zsh

yum install zsh

### Install oh-my-zsh

`wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | sh`

### Install plugins

```shell
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-history-substring-search ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-history-substring-search
```

### zshrc

cp .zshrc ~/.zshrc

Enjoy!


