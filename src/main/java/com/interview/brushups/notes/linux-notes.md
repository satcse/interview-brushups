
# Linux Command

What is Linux - It is an operating system which runs on major computers and other device today.

## Distributions
1. Debian, Ubuntu and Mint Distribution<br/>
 Supports `apt` for package installer

2. Red Hat, Fedora and CentOS<br/>
 Supports `yum` for package installer

## Debian, Ubuntu and Mint Distribution commands

### 1. Install SSH
`sudo apt install openssh-server`

Ubuntu comes with a firewall configuration tool called UFW. <br/>
If the firewall is enabled on your system, make sure to open the SSH port:

`sudo ufw allow ssh`

### 2. Install Cloudera Manager

I. Download Install `.bin` from https://archive.cloudera.com/cm[X]
    `wget https://archive.cloudera.com/cm6/6.3.1/cloudera-manager-installer.bin`

II. Change `cloudera-manager-installer.bin` to have execute permissions:
    `sudo chmod u+x cloudera-manager-installer.bin`
    
III. Run the Installer
     `sudo ./cloudera-manager-installer.bin`    

## Red Hat, Fedora and CentOS



## Common Commands

