

sudo apt-get update
sudo apt-get upgrade
sudo apt-get full-upgrade
sudo apt install git 
sudo apt install raspberrypi-kernel-headers
sudo raspi-config
Interfacing Options > I2C and enable it.
sudo apt install -y i2c-tools
sudo i2cdetect -y 1