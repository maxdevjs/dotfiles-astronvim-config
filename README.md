# dotfiles-astronvim-config

User configuration for [AstroNvim](https://github.com/AstroNvim/AstroNvim)

## What is this

I am testing [AstroNvim](https://github.com/AstroNvim/AstroNvim),
an aesthetic and feature-rich neovim config that is extensible and easy
to use with a great set of plugins (puff).
It provides the base configuration. 

> This repo stores only my $USER configuration, not [AstroNvim](https://github.com/AstroNvim/AstroNvim) itself.

[Managing User Configuration](https://astronvim.github.io/Configuration/manage_user_config) offers a
nice walkthrough.

The main suggestion there is to manage the `$USER` configuration in `$HOME/.config/nvim/lua/user`
(where `nvim` is the cloned [AstroNvim](https://github.com/AstroNvim/AstroNvim)).

My personal setup takes the alternative way (check the `TIP` section:
[Managing User Configuration](https://astronvim.github.io/Configuration/manage_user_config)),
storing the `$USER`configuration in `$XDG_CONFIG_HOME/astronvim`:

```yaml
$  #mv ~/.config/nvim ~/.config/nvimbackup

# clones the base configuration
$  git clone https://github.com/AstroNvim/AstroNvim $XDG_CONFIG_HOME/nvim

# clones the $USER configuration
$  git clone https://github.com/maxdevjs/dotfiles-astronvim-config $XDG_CONFIG_HOME/astronvim
 
```

## License

[AstroNvim](https://github.com/AstroNvim/AstroNvim) is [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) licensed.

This repo is under [Unlicense Yourself: Set Your Code Free](https://unlicense.org/), 
compatible with the original [License list on gnu.org - The Unlicense (#Unlicense)](https://www.gnu.org/licenses/license-list.en.html#Unlicense).
