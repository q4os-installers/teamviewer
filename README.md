# Teamviewer installer for Q4OS

prerequisities to build the installer:
- first read https://www.q4os.org/dqa009.html
- install Q4OS development pack:
 $ sudo apt install q4os-devpack-base

building installer:
- cd into the project directory and run:
 $ dpkg-buildpackage -b -uc -us -tc
