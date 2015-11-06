Nominatim install

The purpose of this script is to install Nominatim with North America on a DigitalOcean 8GB server running Ubuntu 14.04 x64.

Optional step 0) Use screen to avoid killing the script if your connection is disconnected. You can resume by doing screen -r later.

screen

1) Install git on your new machine

sudo apt-get -y install git

2) Clone this project

git clone https://github.com/mnehring/nominatim-install.git

3) Change into directory

cd nominatim-install

4) Run the installer

sudo ./install
