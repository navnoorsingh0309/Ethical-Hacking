# Ethical-Hacking

## Kali-Linux

First you need to install kali linux operating system. If you have any other opertating system either you can have dual boot or you can have virtual machine
Download it form here : https://www.kali.org/get-kali/#kali-platforms

We need to update Kali because there are many updates since image is created. Update it as follows:
1. Use Ctrl+Alt+T for Terminal
2. Type these commands
   ```
   sudo apt update
   sudo apt upgrade
   sudo apt dist-upgrade
   sudo apt autoremove
   ```
   
## Python
First download python idle:
```
sudo apt intall idle3
idle  #To Open idle of python3
```

## Kali-Linux: How to acces root account..

Root account user has access to all terminal commands and file systems and cna alter linux system the way he wants. In newer version of kali linux root account has be disabled so you need to enable it first.

`How to do it`

Open Terminal and type these commands
```
kali-linux@kali:~$sudo passwd
[sudo]password for kali: #type you password
New password:
Retype new password:
paswd: password updated successfully
#This is to Set Root account password

Now you can relogin in linux account using
username:root
password:You set above
```
