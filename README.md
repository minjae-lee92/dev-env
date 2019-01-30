# Setting up dev-env

### Download Zsh
via Homebrew
`brew installg zsh`

`chsh- -s /usr/local/bin/zsh`

### Download 
`git clone --recursive https://github.com/minjae-lee92/dev-env`

## Relocate .vim and .zsh to homedir

`cd dev-env`

`mv .zsh /..`

`mv .vim /..`

## Install Vim Plugins

`cd .vim`

`vim vimrc`

`PlugInstall`

## Source Zsh

`vim zshrc`

`source "$HOME/.zsh/slim.zsh"`

### Screenshot Images
vim
![vim screenshot](https://github.com/minjae-lee92/dev-env/blob/master/img/vim)

zsh
![zsh screenshot](https://github.com/minjae-lee92/dev-env/blob/master/img/zsh)
