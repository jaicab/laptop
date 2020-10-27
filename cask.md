# cask

Download most things in one go with cask. You will need [Homebrew](https://brew.sh/) and then tapping cask.

```
brew tap caskroom/cask
```

Once it's available, do:

```
brew cask install \
    the-unarchiver \
    iterm2 \
    zsh \
    vscode \
    lastpass \
    WebPQuickLook \
    background-music \
    spotify \
    whatsapp \
    slack \
    google-chrome \
    firefox \
    opera \
    figma \
    sketch \
    zeplin \
    vlc \
    flux \
    dropbox \
    google-photos-backup-and-sync \
    megasync \
    transmission \
    appcleaner \
    calibre \
    coconutbattery \
    color-oracle \
    imageoptim \
    imagealpha \
    recordit \
    skyfonts \
    vanilla \
    amphetamine \
    rocket \
    muzzle
```

Finally, manually install the apps that aren't on cask:

- [iA Writer](https://ia.net/writer)
- [Color Picker](https://itunes.apple.com/gb/app/color-picker/id641027709?mt=12)
- [ToothFairy](https://itunes.apple.com/gb/app/toothfairy/id1191449274?mt=12)
- [Next Meeting](https://itunes.apple.com/us/app/next-meeting/id1017470484)
- [Magnet](https://apps.apple.com/app/id441258766)
- [Menu World Time](https://apps.apple.com/gb/app/menu-world-time/id1446377255?mt=12)

Once Dropbox has synced, bring all your preferences with [mackup](https://github.com/lra/mackup).

```
# Install Mackup
brew install mackup

# Launch it and restore your files
mackup restore
```
