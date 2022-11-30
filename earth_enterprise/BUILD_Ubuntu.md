# GEE Build Setup for Ubuntu

## Install Git

Install the system default version:

```bash
sudo apt-get install git
```

Alternatively, install the latest version:

```bash
sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
sudo apt-get install git
```

## Install Git LFS

Execute the following:

```bash
curl -s https://packagecloud.io/install/repositories/github/git-lfs/script.deb.sh | sudo bash
sudo apt-get install git-lfs
```

## Also TODO to build 3rd party libs
for gdal .configure patch all ogdi paths by adding '/lib/ogdi' to lib searching paths

add "/wdir/earthenterprise/earth_enterprise/src/NATIVE-REL-x86_64/lib
/wdir/earthenterprise/earth_enterprise/src/NATIVE-REL-x86_64/lib/ogdi"
to the file /etc/ld.so.conf.d/~local.conf
and run ldconfig

## Install Required Packages
Run the following command:
```
sudo apt-get install autoconf automake cmake dpkg g++ gcc libboost-all-dev libc6 libc6-dev libgtest-dev libstdc++6 libtool libgtk2.0-dev libglib2.0-dev libx11-dev libxcursor-dev libxft-dev libxinerama-dev libxrandr-dev libxmu-dev scons xorg-dev python libxml2-utils libxml2-dev

sudo apt-get install \
libtiff-dev \
sqlite3 \
libsqlite3-dev \


sudo apt-get install
\
alien
autoconf
automake
bison++
bisonc++
cmake
doxygen
dpkg
\
    flex
freeglut3-dev
g++
gcc
gettext
\
    libboost-all-dev
libc6
libc6-dev
libcap-dev
libfreetype6
libfreetype6-dev
\
    libgdbm-dev
libgeos-dev
libgeos++-dev
libgif-dev
libgtest-dev
\
    libjpeg-dev
libjpeg8-dev
libmng-dev
libogdi3.2-dev
\
    libperl4-corelibs-perl
libpng12-0
libpng12-dev 
libpq-dev 
libproj-dev
\
    libstdc++6
libtool
libtiff-dev
libgtk2.0-dev
libglib2.0-dev
\
    libx11-dev
libxcursor-dev
libxerces-c-dev
libxft-dev
libxinerama-dev
\
    libxml2-dev
libxml2-utils
libxmu-dev
libxrandr-dev
libyaml-cpp-dev
\
    openssl
libpcre3
libpcre3-dev
\
    python-dev
python-imaging
python-psycopg2
\
    python-setuptools
python2.7
python2.7-dev
python-git
\
    scons
shunit2
xorg-dev
zlib1g-dev
```
