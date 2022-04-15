# My Awesome List

My awesome list containing everything that's just simply awesome

# Software
- [wushowhide](https://www.majorgeeks.com/mg/getmirror/wushowhide,1.html)
- [HIFI cable](http://vincent.burel.free.fr/VirtualAudioApps/HiFiCableAsioBridgeSetup_v1007.zip)
- [VAC - Virtual Audio Cable](https://vac.muzychenko.net/en/)
- [SoundSwitch](https://soundswitch.aaflalo.me/)
- [Keyboard Chattering Fix](https://www.softpedia.com/get/System/System-Miscellaneous/Keyboard-Chattering-Fix.shtml)
- [MAS](https://github.com/massgravel/Microsoft-Activation-Scripts)
- [KMS_VL_ALL_AIO](https://github.com/abbodi1406/KMS_VL_ALL_AIO)
- [Unlocker](https://filehippo.com/download_unlocker/)
- [StartAllBack](https://www.startallback.com/)
- [MKVToolNix](https://mkvtoolnix.download/downloads.html)
- [FAT32->NTFS & NTFS->FAT32](https://www.diskpart.com/AOMEI-n2f.html)
- [KeePass](https://keepass.info/)
- [Memtest](https://www.memtest86.com/)
- [HWINFO](https://www.hwinfo.com/)
- [Peazip](https://peazip.github.io/)
- [Hitfilm Express](https://fxhome.com/product/hitfilm-express)
- [ShareX](https://getsharex.com/)
- [ILSpy](https://github.com/icsharpcode/ILSpy)
- [Exeinfo PE](http://exeinfo.booomhost.com/)
- [Ventoy](https://www.ventoy.net/en/index.html)
- [BetterDiscord](https://betterdiscord.app/)
- [Revo Uninstaller](https://www.revouninstaller.com/)
- [Hitman Pro](https://www.hitmanpro.com/en-us)
- [NTLite](https://www.ntlite.com/download/)
- [PESTUDIO](https://www.winitor.com/)
- [x64dbg](https://x64dbg.com/)
- [HxD](https://mh-nexus.de/en/hxd/)
- [Virtual Serial Port Driver](https://www.eltima.com/products/vspdxp/)
- [qBittorrent](https://www.qbittorrent.org/)
- [Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns)
- [Process Explorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer)

# Apps
- [KeePassDX](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.free)
- [Joey For Reddit](https://play.google.com/store/apps/details?id=o.o.joey)
- [Bluecord](https://bluesmods.com/bluecord/)
- [Octodroid](https://f-droid.org/en/packages/com.gh4a/)
- [QuickEdit](https://play.google.com/store/apps/details?id=com.rhmsoft.edit)
- [AdGuard](https://adguard.com/en/adguard-android/overview.html)

# Extensions
- [Ublock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
- [ClearURLS](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk)
- [HTTPS Everywhere](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp)
- [Decentraleyes](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj)
- [Sponsorblock](https://chrome.google.com/webstore/detail/sponsorblock-for-youtube/mnjggcdmjocbbbhaepdhchncahnbgone)
- [Return Youtube Dislike](https://chrome.google.com/webstore/detail/return-youtube-dislike/gebbhagfogifgggkldgodflihgfeippi)
- [Fastforward](https://chrome.google.com/webstore/detail/fastforward/icallnadddjmdinamnolclfjanhfoafe)
- [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg)
- [Shodan](https://chrome.google.com/webstore/detail/shodan/jjalcfnidlmpjhdfepjhjbhnhkbgleap)

# Website utils
- [Temp-Email](https://temp-mail.org/)
- [8MB video](https://8mb.video/)
- [Image to text converter](https://www.prepostseo.com/image-to-text)
- [Youtube video downloader](https://yt1s.io/)
- [Diffchecker](https://www.diffchecker.com/)
- [Down checker](https://downforeveryoneorjustme.com/)
- [ASCII utils](https://www.asciitohex.com/)
- [VirusTotal](https://www.virustotal.com/)

# Actually legit pirate websites
- 1337x
- S0ft4pc
- Portable4pc
- CS.RIN.RU
- AppNee
- SadeemPC

# ISO deployment notes

### Changing Windows license types
You can use MAS

### Windows creation tool
The USB is converted to FAT32 and not NTFS

### Ubuntu with Secureboot + UEFI native
Customized boot in first
```
EFI\ubuntu\shimx64.efi
```

### Windows with Secureboot + UEFI native
UEFI with CSM (NTFS MBR)
```
mbr2gpt /disk:0 /convert /allowFullOS
```
Boot in UEFI native (without CSM) and Secureboot

### Azure Windows keys
They can be used infinitely, but after 3 times you have to verify by SMS
