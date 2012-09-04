#.vim configuration files: Taihen Vim Distribution

This is a distribution of vim plugins and tools intended to be run on top of VIM. It is a good starting point for anyone intending to use VIM for development.

##Manual installation:
'''
cd ~
git clone https://github.com/taihen/vimfiles.git .vim
ln -s .vim/vimrc .vimrc
'''
##Updating to the latest version:
'''
cd ~/.vim
git pull
git submodule sync
git submodule update --init --recursive
'''