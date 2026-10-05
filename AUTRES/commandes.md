---
aliases:
  - Untitled
tags: []
size: 50
color: "#888888"
---
SPICETIFY


mkdir -p ~/.config/spicetify/Themes/marketplace

spicetify config current_theme marketplace

spicetify apply

---
CURSEFORGE :
cd ~/Downloads && chmod +x curseforge-latest-linux.AppImage && ./curseforge-latest-linux.AppImage

cd minecraft_server
java -Xmx12288M -Xms12288M -jar fabric-server-mc.26.3-loader.0.19.5-launcher.1.1.2.jar server nogui

 sudo mkdir -p /run/playit && sudo chown codespace:codespace /run/playit && playitd &
