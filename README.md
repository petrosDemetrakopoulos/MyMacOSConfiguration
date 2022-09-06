# My Mac configuration
This is my Mac configuration and setup for Software development & Machine learning projects.
Feel free to use it.

## Desktop apps

### Development
- Mozilla Firefox [Download link](https://www.mozilla.org/en-US/firefox/new/)
- VS Code [Download link](https://code.visualstudio.com/download)
- Xcode [Download link](https://apps.apple.com/us/app/xcode/id497799835?mt=12)
- SourceTree [Download link](https://www.sourcetreeapp.com/)

### Utilities
- iTerm 2 [Download link](https://iterm2.com/downloads.html)
- Postman [Download link](https://www.postman.com/downloads/)
- Adapter [Download link](https://macroplant.com/adapter)
- Sublime Text [Download link](https://www.sublimetext.com/download)
- FileZilla (FTP Client) [Download link](https://filezilla-project.org/download.php?type=client)
- Beekeeper Studio (Community Edition) [Download link](https://www.beekeeperstudio.io/get)
- TeamViewer [Download link](https://www.teamviewer.com/en/download/mac-os/)

### Maintenance
- CleanMyMac [Download link](https://macpaw.com/cleanmymac)

## Communication
- Zoom [Download link](https://zoom.us/download)
- MS Teams [Download link](https://www.microsoft.com/en-us/microsoft-teams/download-app)
- Slack [App Store link](https://apps.apple.com/us/app/slack-for-desktop/id803453959?mt=12)

## Package Managers
- Homebrew [Installation guide](https://brew.sh/)
- PIP [Installation guide](https://www.groovypost.com/howto/install-pip-on-a-mac/)
- Yarn (Installed with `npm install --g yarn`)

## Tools and languages
- Node.JS and NPM [Download link](https://nodejs.org/en/download/)
- React (Installed with `npm install -g create-react-app`)
- Python [Download link](https://www.python.org/downloads/)
- Docker Desktop [Download link](https://www.docker.com/products/docker-desktop/)
- mySQL (Installed with `brew install mysql`)
- MongoDB (Installed with `brew install mongodb`)
- Redis (Installed with `brew install redis`)
- RStudio [Download link](https://www.rstudio.com/products/rstudio/download/)

## CLI apps
- git (Installed with `brew install git`)
- wget (Installed with `brew install wget`)
- heroku (Installed with `brew install heroku`)
- ganache (Installed with `npm install -g ganache`)
- htop (Installed with `brew install htop`)
- curl (Installed with `brew install curl`)
- nvm - Node version manager (Installed with `npm install -g nvm`)
- http-server (Installed with `npm install -g http-server`)
- iponmap (Installed with `npm install -g iponmap`)
- pyenv (Installed with `brew install pyenv`)
- tree (Installed with `brew install tree`)

## Terminal configuration
- Oh My ZSH [Installation guide](https://ohmyz.sh/#install)

### Oh My ZSH plugins
- zsh-autosuggestions (Installed with `brew install zsh-autosuggestions`)
- zsh-syntax-highlighting (Installed with `brew install zsh-syntax-highlighting`)

## Python libraries and packages
- matplotlib (Installed with `pip install matplotlib`)
- SciKitLearn (Installed with `pip install scikit-learn`)
- XGBoost (Installed with `pip install xgboost`)
- TensorFlow (Installed with `pip install tensorflow`)
- Keras (Installed with `pip install keras`)
- Keras RL2 (Installed with `pip install keras-rl2`)
- NumpPy (Installed with `pip install numpy`)
- Pandas (Installed with `pip install pandas`)
- Gym (Installed with `pip install gym`)

## VS Code Extensions
- Prettier - Code formatter
- Truffle for VS Code
- Python
- Jupyter
- ESLint
- DotENV

## Specials for M1 Macs

**Before installing anything else** it is important to install Rosetta2 emulator.
You can do so with the following terminal command:
```
/usr/sbin/softwareupdate --install-rosetta --agree-to-license
```

## System preferences

### Show all hidden files
```
defaults write com.apple.Finder AppleShowAllFiles true
killall Finder
```

### Show User Library folder
```
chflags nohidden ~/Library/
killall Finder
```

## Disable the “Are you sure you want to open this application?” dialog
```
defaults write com.apple.LaunchServices LSQuarantine -bool false
```

## Finder show path bar
```
defaults write com.apple.finder ShowPathbar -bool true
```

## Display the file extensions in Finder
```
defaults write NSGlobalDomain AppleShowAllExtensions -bool true
killall Finder
```

## When performing a search, search the current folder by default
```
defaults write com.apple.finder FXDefaultSearchScope -string "SCcf"
```

## Expand save panel by default
```
defaults write NSGlobalDomain NSNavPanelExpandedStateForSaveMode -bool true
defaults write NSGlobalDomain NSNavPanelExpandedStateForSaveMode2 -bool true
```
