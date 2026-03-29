plugins chmod
`find . -type f -name "*.sh" -exec chmod +x {} \;`

font/icons
`brew install --cask sf-symbols`

symlinking bottombar `ln -s $(which sketchybar) $(dirname $(which sketchybar))/bottombar`