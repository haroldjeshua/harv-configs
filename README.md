# harv-configs

## linux env setup
#### ZSH Z-shell + [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)

`sudo apt install zsh` <br>
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"` <br>
`code ~/.zshrc` ← customize it <br>

### Preferred Theme:
[Vercel Theme](https://github.com/vercel/zsh-theme) <br>
`curl https://raw.githubusercontent.com/vercel/zsh-theme/master/vercel.zsh-theme -Lo ~/.oh-my-zsh/custom/themes/vercel.zsh-theme` <br>
Edit your `~/.zshrc`: <br>
`ZSH_THEME="vercel"`

See more [Oh My Zsh Themes](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)

### Oh My Zsh Plugins
[autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
[syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)

### Node + Node.js with NVM
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash` <br>
In `~/.zshrc`: <br>
`plugins=(git nvm)` <br>

Install node:
```
nvm install --lts

node -v
npm -v
```

## windows env setup
[wsl setup guide](https://fireship.io/lessons/windows-10-for-web-dev/)
