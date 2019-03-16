# Some Equilux fork
forked from: https://github.com/ddnexus/equilux-theme

I changed some things but forgot what and I'm too lazy to backtrack all that :)

## Installation
```
# theme
git clone https://github.com/hyphenc/Equilux-compact
sudo mv Equilux-compact/ /usr/share/themes/
gsettings set org.gnome.shell.extensions.user-theme name "Equilux-compact"

# gdm theme
cd /usr/share/themes/Equilux-compact/gnome-shell/
sudo glib-compile-resources --target=/usr/share/gnome-shell/gnome-shell-theme.gresource gnome-shell-theme.gresource.xml
restart the session (logout)
```
