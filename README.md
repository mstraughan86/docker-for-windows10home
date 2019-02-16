# Docker for Windows 10 Home
Installation instructions to install Docker for Windows on Windows 10 Home. Instructions found at https://forums.docker.com/t/installing-docker-on-windows-10-home/11722/29

- Run ```install_hyperv_packages.bat```
- Do not restart.
- Run ```install_containers_packages.bat```
- Restart.
- Run ```os-change.reg```
---
- Run ```https://download.docker.com/win/stable/Docker%20for%20Windows%20Installer.exe```

Or if you are coming from [these instructions](https://github.com/mstraughan86/modern-development/),

- Chocolatey Alternative : ```(powershell as admin)``` ```choco install docker-for-windows -y```
---
- Run ```os-restore.reg```
- Restart.
