# dotfiles
My dotfiles
 
 
 This is a thing:
 ```
git init --bare $HOME/.dotfiles
alias config='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
config config --local status.showUntrackedFiles no
 
 ```
