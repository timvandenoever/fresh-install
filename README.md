# fresh-install
This repository has most of the necessary files/steps to setup a machine after a fresh install

- Install Brew: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
- Install Alfred/Spectacle: `brew cask install alfred spectacle`
- Install Chrome/PHPStorm/Sequel Pro/Postman/Slack/Iterm2
- Create global git hooks folder: `mkdir -p ~/.git/hooks`
- Copy `prepare-commit-msg` to `~/.git/hooks`
- Make the file executable: `chmod +x ~/.git/hooks/prepare-commit-msg`
- Copy `.gitconfig` and fill in placeholders
