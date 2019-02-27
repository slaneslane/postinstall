sudo apt-get update
sudo apt-get upgrade
sudo apt-get update --fix-missing
sudo apt autoremove


# instalacja podstawowych programów:
sudo apt-get install git curl tree vim gvim tmux zsh python-pip python-dev python-gdal gparted synaptic dconf-tools gnome-tweak-tool unity-tweak-tool gnome-games 

# instalacja python3.6: https://askubuntu.com/questions/865554/how-do-i-install-python-3-6-using-apt-get

sudo apt-get install python3-pip python3.6-venv

# Zmapuj CapsLock jako escape:
gsettings set org.gnome.desktop.input-sources xkb-options "['caps:escape']"

or if not working then:

setxkbmap -option <OPTION>
Where <OPTION> can be for example of:

caps:none – Disables Caps Lock.
caps:super – Caps Lock becomes an additional Super (aka Win key).
caps:ctrl_modifier – Caps Lock becomes an additional Ctrl.
caps:numlock – Caps Lock becomes an additional Num Lock.
caps:escape – Caps Lock becomes an additional Escape.
caps:backspace – Caps Lock becomes an additional Backspace.
caps:swapescape – Caps Lock becomes Escape, and Escape becomes Caps Lock



# Zainstaluj NeoVim -> osobny plik w tym katalogu.


# Zainstaluj powerline -> osobny plik w tym katalogu.


# Dostosuj środowisko edytora Vim i NeoVim korzystając z:
# https://www.youtube.com/watch?v=vlb3qUiS2ZY&t=322s
# http://fisadev.github.io/fisa-vim-config/


# Zainstaluj JAVA 10 -> osobny plik w tym katalogu.


# instalacja Google Chrome:
wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -
echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' | sudo tee /etc/apt/sources.list.d/google-chrome.list
sudo apt-get install google-chrome-stable


# instalacja Eclipse (po pobraniu rozpakuj poniższą komendą a następnie uruchom):
tar -xvf ~/Pobrane/eclipse-inst-linux64.tar.gz 
