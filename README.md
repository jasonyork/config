This is a repo I've set up to store my user preferences.  It uses oh-my-zsh shell and has some git settings.  

To get started:
```
cd ~
git clone git@github.com:jasonyork/config.git .
```

Then to pull in oh-my-zsh:
```
git submodule init
git submodule update
```

Set zsh as your default shell:
```
chsh -s /bin/zsh
```

Set your git username and email
```
git config --global user.name "Your name here"
git config --global user.email "you@example.com"
```

Start / restart zsh (open a new terminal)
