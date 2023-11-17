# Fish

## Install
```
brew install fish
```

## Make `fish` default shell
```
echo (command -s fish) | sudo tee -a /etc/shells
chsh -s $(command -s fish)
```

## Configure Path
```
fish_add_path /opt/homebrew/bin
```
