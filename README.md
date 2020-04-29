# dotfiles

```sh
env LANGUAGE=C LC_MESSAGES=C xdg-user-dirs-gtk-update
sudo apt update && sudo apt dist-upgrade -y && sudo apt autoremove && sudo apt clean
sudo apt install git vim terminator cairo-dock cairo-dock-gnome-integration-plug-in compizconfig-settings-manager compiz-plugins compiz-plugins-extra unity-lens-applications unity-lens-files unity-tweak-tool gedit-plugins nemo unity-session gparted yarn mysql-server libmysqlclient-dev graphviz gparted vlc kicad inkscape gimp blender ubuntu-restricted-extras
wget https://raw.githubusercontent.com/swanmatch/dotfiles/master/.bash_aliases
wget https://raw.githubusercontent.com/swanmatch/dotfiles/master/.vimrc
wget https://raw.githubusercontent.com/swanmatch/dotfiles/master/.inputrc
sudo timedatectl set-local-rtc true
```

1. dockを自動的に隠す。サイズをいい感じにする。
2. 壁紙をいい感じにする。
3. unity-tweak-toolより、panelのopacityを無効にする。他適当に。
4. compizconfig-settin-managerより、揺れるウィンドウ、アプリケーションスイッチャー、JPEG、デスクトップキューブ、キューブの回転、animations-addonを有効にする。  
  アニメーションをいい感じにする。  
  デスクトップサイズを4にして、デスクトップキューブのスカイキューブを設定する。
5. firefox acountにログインしてのabout:configより、backspace-actionを0にする。
6. geditをいい感じにする。
7. cairo-dockのthemeをchromeにする。
