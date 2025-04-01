# z.lua.yazi

A yazi plugin for z.lua integration

## Install

```sh
ya pack -a hopenobug/z-lua
```

Make sure you have lua installed and $ZLUA_SCRIPT is set to absolute path of z.lua.

## Usage

Edit `$XDG_CONFIG_HOME/yazi/keymap.toml`:

```toml
[manager]
prepend_keymap = [
	{ on = [ "z" ], run = "plugin z.lua", desc = "Jump to a directory using z.lua" },
]
```
