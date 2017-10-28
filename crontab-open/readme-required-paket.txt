##webmin installation

sudo nano /etc/apt/sources.list

# am ende der Datei folgendes einfügen und mit Strg + x speichern: deb http://download.webmin.com/download/repository sarge contrib

wget http://www.webmin.com/jcameron-key.asc
sudo apt-key add jcameron-key.asc

sudo apt install webmin vlc