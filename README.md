### dotfiles
---
https://github.com/thoughtbot/dotfiles

```sh
cd dev/thoughtbot/dotfiles

chsh -s $(which zsh)

git clone git://github.com/thoughtbot/dotfiles.git ~/gotfiles

brew tap thoughtbot/formulae
brew install rcm


env RCRC=$HOME/dotfiles/rcrc rcup
rcup

mkdir ~/dotfiles-local



```


```
alias todo='$EDITOR ~/.todo'

/*
~/dotfiles-local/vimrc.local
*/



```



