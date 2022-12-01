**Linux Mint Virtual Machine** </br>
Create a Linux Mint Virtual Machine on your computer. Check the distribution, which package manager it uses (yum, apt, apt-get). Which CLI editor is configured (Nano, Vi, Vim). What software center/software manager it uses. Which shell is configured for your user.


> SOLUTION:

>> Step1: Download Linux Mint ISO file from https://linuxmint.com/download.php
>> Step2: Verify ISO image by following steps mentioned here https://linuxmint-installation-guide.readthedocs.io/en/latest/verify.html
>> Step3: Install VirtualBox from Ubuntu Softwares
>> Step4: Install linux mint on virtual box.

1. Checking distribution of OS
 cat /etc/os-release
 
NAME="Linux Mint"
VERSION="21 (Vanessa)"
ID=linuxmint
ID_LIKE="ubuntu debian"
PRETTY_NAME="Linux Mint 21"
VERSION_ID="21"
HOME_URL="https://www.linuxmint.com/"
SUPPORT_URL="https://forums.linuxmint.com/"
BUG_REPORT_URL="http://linuxmint-troubleshooting-guide.readthedocs.io/en/latest/"
PRIVACY_POLICY_URL="https://www.linuxmint.com/"
VERSION_CODENAME=vanessa
UBUNTU_CODENAME=jammy


2. Package managers of OS - apt, apt-get
3. CLI Editor - Nano
4. Software Center/manager - Synaptic Package Manager, software manager
5. Which shell is configured for your user
echo $SHELL - /bin/bash 
bash shell
