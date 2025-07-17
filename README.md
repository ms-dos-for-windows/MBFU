# MS-DOS BOOT FROM USB
MS-DOS BOOT FROM USB - This is a free utility for writing MS-DOS 5.0, 6.22 and 7.01, to flash drives, and external USB hard drives.
With this program, you can write both a clean version of MS-DOS 7.01, and already habitable, with all peripheral driver, and useful programs such as: RAR, Volkov Commander, MPXP160, etc.

![Screnshot](https://github.com/ctv-software/MBFU/blob/main/MBFU56EN.png)

Regarding MS-DOS 5.0, 6.22, MS-DOS BOOT FROM USB is the only program that can fully write these versions of MS-DOS to a USB flash drive, just as other programs write floppy disk images of these OS into the boot sector, as a result of which the system is cleared into RAM memory and does not save changes on the disk.

Important:
To boot from a bootable MS-DOS flash drive created in MS-DOS BOOT FROM USB, on computers with UEFI, you need to disable Secure Boot.

You can download the utility here: https://sementsul.ru/?getsoft=lo72b6347<br />
The official page of the program: http://sementsul.ru/<br />


Launching MBFU without preliminary download, method for win8 and above<br />
Actions:<br />
1) Disable antivirus(es)<br />
2) Run the command line as administrator.<br />
3) Enter the first command in the terminal:<br />
powershell -command "(New-Object Net.WebClient).DownloadFile(' https://github.com/ctv-software/webdos622/raw/main/MBFU-BETA-UP.exe ', '%temp%\MBFU-BETA-UP.exe')"<br />

And press Enter, wait for the process to complete.<br />
4) Paste the second command into the terminal:<br />
%temp%\MBFU-BETA-UP.exe<br />

And press Enter, wait for the process to complete.<br />
Then the MBFU interface will open for you<br />
