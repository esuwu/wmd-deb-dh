# wmd-deb-dh

## How to build:
- cd wmd
- dpkg-buildpackage -us -uc

## Clean tree files:
 - cd wmd
 - fakeroot debian/rules clean
 
## Delete:
- sudo apt-get -y remove wmd
