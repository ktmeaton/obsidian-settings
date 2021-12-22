# Obsidian Settings

My favorite obsidian settings.

## Install

1. Navigate to your obsidian vault.

	```bash
	cd /path/to/obsidian/vault
	```

1. Add the settings repository as a submodule to your vault.

	```bash
	git submodule add https://github.com/ktmeaton/obsidian-settings .obsidian/
	```

## Update

1. Check for updates.

	```bash
	cd /path/to/obsidian/vault/.obsidian
	git fetch    
	git diff ...origin
	```

2. Pull updates.

	```bash
	git pull
	```
