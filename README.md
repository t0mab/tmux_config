tmux_config
===========

## Install

* git clone https://github.com/t0mab/tmux_config/ ~/.config/tmux
* ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf

## local conf

If you need special parameters on selected host & os

Put a .tmux.conf.local in your home

eg : for mac if you have reattach-to-user-namespace (brew install...) :

ln -s ~/.config/tmux/tmux.conf.local.osx ~/.tmux.conf.local
