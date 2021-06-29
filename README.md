# Codigos
#para conectar las raspberry por una videoconferencia (primero teníamos que instalar PIXEL en nuestro escritorio)
apt-get update
apt-get upgrade
sudo apt install raspberrypi-ui-mods
sudo apt-get install --no-install-recommends xserver-xorg
sudo apt-get install --no-install-recommends xinit
sudo apt-get install raspberrypi-ui-mods
sudo apt-get install -y rpi-chromium-mods
sudo apt-get install -y python-sense-emu-doc realvnc-vnc-viewer
sudo apt-get install -y python-sense-emu python3-sense-emu python-sense-emu-doc
sudo apt-get install lightdm
sudo reboot
# ahora solo nos conectamos a una reunion que tenemos que crear en Jitsi meet la cual comunicara la camara de las 2 raspberry por videoconferencia
