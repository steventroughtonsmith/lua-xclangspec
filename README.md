# lua-xclangspec

This adds syntax highlighting for Lua source files to Xcode. Packaged for Xcode 9.2 from original repo at https://github.com/bastos/lua-xcode-coloring.

## Installation

### Setup script

Run the following command in your terminal:

```
./setup.sh
```

### Manual installation

Please note that if you are running Xcode 8 the `Plug-ins` and `Specifications` directories might not exist.

- Copy the Lua.ideplugin` directory to `~/Library/Developer/Xcode/Plug-ins/`:

	```
	cp -r Lua.ideplugin ~/Library/Developer/Xcode/Plug-ins/
	```
- Copy the `Lua.xclangspec` file to `~/Library/Developer/Xcode/Specifications`:

	```
	cp Lua.xclangspec ~/Library/Developer/Xcode/Specifications/
	```
