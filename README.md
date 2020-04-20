# dotfiles

## Setup:

Initalize a git bare repo , add alias to .bashrc and set the required settings. 
```
git init --bare ~/.myconfig
echo "alias df='/usr/bin/git --git-dir=$HOME/.myconfig/ --work-tree=$HOME'" >> $HOME/.bashrc
bash
df config status.showUntrackedFiles no
```

