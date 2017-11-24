# mac-playbook
Ansible playbook for setting up a Mac.
This utilizes a [brew bundle file](https://github.com/Homebrew/homebrew-bundle), [mas](https://github.com/mas-cli/mas), and a few other taps to set up the apps I like, as well as my `dotfiles.`

# requirements
1. Ensure you have the _full_ version of XCode installed for High Sierra.  Otherwise the command-line install should work fine.
2. Install homebrew: 
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
3. `brew install ansible`

# usage
`ansible-playbook main.yml -i inventory -K`

# todo

1. execute osx script
1. add custom bash aliases and what not to installation
1. ensure `.bashrc` exists and is sourced properly