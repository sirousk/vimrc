# vimrc
My Personal Vim Configuration

## Setup

Copy .vimrc file to USER's home directory. It will replace your default .vimrc file, if you want \
to keep your default config file make a backup from it before running the following command.

`
$ cp vimrc/.vimrc ~
`

Next you need to install Vundle vim plugin manager. \
The Vundle github repository should be cloned in the ".vim/bundle/Vundle.vim" in the USER’s home directory.

git clone https://github.com/VundleVim/Vundle.vim ~/.vim/bundle/Vundle.vim

Now open vim 

`
$ vim
`

Run the following VIM command to initialize Vundle Plugin Manager:

`
:PluginInstall
`

This my take you a while, wait until all the plugins installed completely.
