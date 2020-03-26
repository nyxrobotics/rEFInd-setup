### install rEFInd[1]
- Download the latest rEFInd from sourceforge[2]
- if you have already installed old version, remove it[3]

		sudo dpkg -P refind
		sudo rm -rf /boot/efi/EFI/refind
		sudo rm //boot/refind_linux.conf

- install rEFInd

		sudo dpkg -i refind_0.12.0-1_amd64.deb 

- If you need, install theme[4]

- If the rEFInd GUI doesn't work, set "textonly" mode [5],[6]


### References
[1]https://www.rodsbooks.com/refind/installing.html  
[2]https://sourceforge.net/projects/refind/  
[3]https://askubuntu.com/questions/856773/how-to-remove-refind-drivers-completely-from-my-ubuntu  
[4]https://github.com/EvanPurkhiser/rEFInd-minimal  
[5]https://wiki.ubuntulinux.jp/UbuntuTips/Install/UEFI/rEFInd%20Boot%20Manager  
[6]https://orumin.blogspot.com/2014/07/linuxrefind.html  