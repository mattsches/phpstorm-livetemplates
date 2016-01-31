# PHPStorm LiveTemplates

## Installation

First, find your configuration folder.

	Windows: <your home directory>\.WebIde<version>\config
	Linux: ~\.WebIde<version>\config
	MacOS: ~/Library/Preferences/WebIde<version>

On my linux, it would be <code>~/.WebIde110/config</code> so you have to adjust commands to your platform. There is a <code>templates/</code> directory. It contains XML files with Live Templates.

Create a git repository in the `templates/` dir and pull the templates

	$ cd ~/.WebIde110/config/templates/
	$ git init
	$ git remote add origin git://github.com/mattsches/phpstorm-livetemplates.git
	$ git pull origin master

If this wouldn't work, you should just backup your templates, clone the repo and merge them manually.

## Acknowledgements

Inspired by [fprochazka/phpstorm-livetemplates](https://github.com/fprochazka/phpstorm-livetemplates)
