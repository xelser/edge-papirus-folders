# About
This is based on Catppuccin's [papirus-folders](https://github.com/catppuccin/papirus-folders) for Sainnhe's [Edge Colorscheme](https://github.com/sainnhe/edge)

| Red | Yellow | Green | Cyan | Blue | Purple |
|:---:|:------:|:-----:|:----:|:----:|:------:|
|![Red](src/64x64/places/user-edge-red-home.svg)|![Yellow](src/64x64/places/user-edge-yellow-home.svg)|![Green](src/64x64/places/user-edge-green-home.svg)|![Cyan](src/64x64/places/user-edge-cyan-home.svg)|![Blue](src/64x64/places/user-edge-blue-home.svg)|![Purple](src/64x64/places/user-edge-purple-home.svg)|

# Install
1. Make sure You have [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) installed
2. Clone this repository and change to cloned directory:

```sh
git clone https://github.com/xelser/edge-papirus-folders && cd edge-papirus-folders
```
3. Copy content of `src` to Papirus Directory:
```sh
sudo cp -r src/* /usr/share/icons/Papirus/ # if installed in the root
```
```sh
cp -r src/* $HOME/.local/share/icons/Papirus/ # if installed in $HOME
```
4. Use modified `papirus-folders` script to set colors of folders.
```sh
./papirus-folders -C edge-blue --theme Papirus-Dark
```
Available colors are: `edge-red`, `edge-yellow`, `edge-cyan`, `edge-green`, `edge-blue`, `edge-purple`
#### Visit [Papirus-folders](https://github.com/PapirusDevelopmentTeam/papirus-folders) and [Catppuccin Papirus-Folders](https://github.com/catppuccin/papirus-folders) to learn more about this script

# Credits
- [Catppuccin's Papirus Folders](https://github.com/catppuccin/papirus-folders)
- [Papirus Team](https://github.com/PapirusDevelopmentTeam)
- [Edge Colorscheme](https://github.com/sainnhe/edge)

This project wouldn't be possible without any of the above. Show them great support :heart:

# License
[GPL-3.0](./LICENSE) © xelser
