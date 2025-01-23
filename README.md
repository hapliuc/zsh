# ~/.config/zsh

Simple and structured `zsh` configuration with modularity in mind.

## Installation

1. Clone repository into `~/.config` directory:
```console
$ git clone https://github.com/hapliuc/zsh.git ~/.config/zsh
```

2. Create `/etc/zsh/zshenv` file and set the `$ZDOTDIR` variable:
```console
# touch /etc/zsh/zshenv
# echo 'export ZDOTDIR=$HOME/.config/zsh/config/core' > /etc/zsh/zshenv
```

3. Clone required plugins into the `~/.config/zsh/plugins/` folder:
```console
$ git clone https://github.com/jeffreytse/zsh-vi-mode.git ~/config/zsh/plugins/zsh-vi-mode
```

4. Change default shell:
```console
$ chsh -s $(which zsh)
```

