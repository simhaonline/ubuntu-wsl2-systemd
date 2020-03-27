# wsl2-systemd
Script to enable systemd support on current Ubuntu WSL2 images from the Windows store. 

# Usage
### Run the script and commands
```sh
git clone https://github.com/simhaonline/wsl2-systemd.git
cd wsl2-systemd/
sudo bash wsl2-systemd.sh
# Enter your password and wait until the script has finished
cmd.exe /C setx WSLENV BASH_ENV/u
cmd.exe /C setx BASH_ENV /etc/bash.bashrc
```
### Then restart the shell and try running systemctl
```sh
systemctl
```
# Have fun using systemd on WSL2. 
