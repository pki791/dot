# Installation

Install:
- homebrew (mac only)
- oh-my-zsh
- fzf
- git
- stow
- **nano**
- fonts JetBrains Nerd from https://www.nerdfonts.com/font-downloads
- powerlevel10k from https://github.com/romkatv/powerlevel10k?tab=readme-ov-file#oh-my-zsh
- zsh-syntax-highlighting as plugin with
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

Check out the files into $HOME

```
git clone https://github.com/pki791/dot.git
```
```
cd dot
stow zsh
stow nano-mac

```

