# Blaster

_Malware profile by **[Marc Cser](https://github.com/mcser)**_

### Classification

| Virus | Worm               | Trojan | Ransomware | Botnet | Other |
|:------|:-------------------|:-------|:-----------|:-------|:------|
|       | :heavy_check_mark: |        |            |        |       |

### Facts & Figures

* **Year:** 2003 \[[^1]\]
* **Author:** Xfocus \[[^2]\]
* **Language:** C \[[^3]\]
* **Infections:** >423,000 computers \[[^4]]\, 8-16 million maximum infections according to Microsoft \[[^3]\]
* **Damage:** $320 million \[[^3]\]

### Description

> This worm was first noticed on August 11 of 2003. By August 18 of 2003, over 423,000 computers were reportedly infected.
>
> Blaster works only on Windows 2000 and Windows XP. However, since these were the most widespread variants of Windows at the time, the number of affected users was relatively large.
>
> Blaster used a vulnerability in the Windows system which caused infected systems to be able to send malicious code to other systems in the same network through TCP port 135, which would then be executed.
>
> This code is used to open a connection to a remote command shell, which starts a TFTP server listening on UDP port 69 on the target machine. It will then download the worm through this port.
>
> The worm then runs itself, and adds itself to the registry such that it will start up with every Windows boot, and seek new computers to infect.
>
> The worm was used to create a botnet using the infected systems.
>
> The Blaster worm shut down CTX, the largest railroad system in the Eastern U.S., for hours, crippled the new Navy/Marine Corps intranet, shut down Air Canada's check-in system and has been implicated in the severety of the Northeast blackout. Maryland Motor Vehicle Administration authority shut its offices for the day because its systems were so severely affected by Blaster that it could no longer continue as normal. Other organisations reportedly suffering network slowdowns or worse because of the worm include German car manufacturer BMW, Swedish telco TeliaSonera, the Federal Reserve Bank of Atlanta and Philadelphia's City Hall. Damage totalled to $320 million.
>
> \[[^3]\]

[^1]: https://www.infoworld.com/article/2677291/security/blaster-worm-spreading--experts-warn-of-attack.html
[^2]: https://web.archive.org/web/20081101140521/http://www.vnunet.com/vnunet/news/2123165/fbi-arrests-stupid-blaster-b-suspect
[^3]: http://virus.wikia.com/wiki/Blaster
[^4]: https://www.infoworld.com/article/2677039/security/blaster-worm-attack-a-bust.html
