# dotfiles

# zsh

## Installation

```sh
apt install zsh zsh-autosuggestions zsh-syntax-highlighting
```

## Config

Create config directory:

```sh
mkdir .config/zsh
```

- Copy `.zshrc` to home directory
- Copy `zsh*` functions/files to `.config/zsh`
- Add to `.bashrc` [this](https://github.com/stevomat/dotfiles/blob/5140aaa14b9030c30b72c1636e5c87f6e3be8f49/zsh/.bashrc#L119-L120) 
- Restart terminal
> You can also work with symlinks

## Font 

https://ostechnix.com/install-nerd-fonts-to-add-glyphs-in-your-code-on-linux/

For correct display of the glyphs in the terminal I use *JetBrainsMono Nerd Font Mono Medium* (patched font!):

```sh
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/JetBrainsMono.zip
```
Copy all files to `/usr/share/fonts` or `~/.local/share/fonts` and then:

```sh
fc-cache -fv
```

Change the font in the terminal
