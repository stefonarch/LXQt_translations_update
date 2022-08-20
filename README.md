# Updated Translation files for LXQt

Archive containing updated translations for all LXQt components, menus and applications, including PCmanFm-qt, LXimage-qt, qps, ScreenGrab QTerminal and lxqt-archiver.

Warning: this is still beta, use at your own risk.

## Installation

### For all users, overwriting existing files:

```
wget https://github.com/stefonarch/LXQt_translations_update/raw/main/lxqt-translations-update.tar.gz
tar xf lxqt-translations-update.tar.gz
cd translations
sudo cp -av usr /
```

### Only for current user (menu entries and LXQt-Components, without lxqt-panel and applications):

```
wget https://github.com/stefonarch/LXQt_translations_update/raw/main/lxqt-translations-update.tar.gz
tar xf lxqt-translations-update
cd translations
mkdir -p ~/.local/share/applications
cp -v usr/share/applications/* ~/.local/share/applications/
cp -v usr/share/lxqt ~/.local/share/
```




