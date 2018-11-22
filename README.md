# VSCode profil

### Settings

Copy `keybindings.json` and `settings.json` to `~/Library/Application Support/Code/User/`

### Extensions

A list of all used extensions is contained in `extensions.txt`

Generate extension-list:
```
"/Applications/Visual Studio Code.app//Contents/Resources/app/bin/code" --list-extensions
```

Install extensions:
```
--install-extension <ext> //see 'code --help'
```

### jsconfig

Setup for the shop-web-client project

* adjustes abosulte path (in-app resolved via special resolver module)
* excludes all the glitter
