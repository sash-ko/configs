## vim

- Install [Vundle](https://github.com/VundleVim/Vundle.vim):
  ```
  git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
  ```
  
- Run `VundleInstall`

- Install [vim-plug](https://github.com/junegunn/vim-plug):
  ```
  curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
  ```
  
- Run `PlugInstall`

## Oh My Zsh

- Install [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh):
  ```
  sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
  ```
  
- Install [starship](https://starship.rs/):
  ```
  brew install starship
  ```
  
- Install [fzf](https://github.com/junegunn/fzf):
  ```
  brew install fzf
  ```
  
- Install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions):
  ```
  git clone https://github.com/zsh-users/zsh-autosuggestions \
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
  ```
  
- Install [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting):
  ```
  git clone https://github.com/zsh-users/zsh-syntax-highlighting.git \
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
  ```
  
- Copy `starship.toml` to `~/.config/`

- Use: 
  * **ctrl+r** - search
  * **ctrl+t** - cd folders
