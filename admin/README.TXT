------------------------------
Update:
sudo apt update -y
------------------------------
Update linux headers:
sudo apt-get install linux-headers-generic
sudo apt-get install linux-headers-3.5.0-31-generic 
------------------------------
Build and install:
make 
sudo make install
sudo insmod 8821cu.ko
------------------------------
Tested on:

    Host machine: Ubuntu 20.04.5 LTS
    Linux 5.4.0-146-generic x86_64
    gcc (Ubuntu) 9.4.0 
    GNU ld (GNU Binutils for Ubuntu) 2.34

    Host machine: Ubuntu 22.04.2 LTS
    Linux 5.15.0-75-generic x86_64
    gcc (Ubuntu) 11.3.0 
    GNU ld (GNU Binutils for Ubuntu) 2.38





