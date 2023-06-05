# Free disk space in Windows automatically

```powershell
Optimize-VHD -Path $Env:LOCALAPPDATA\Docker\wsl\data\ext4.vhdx -Mode Full
```

```cmd
del /q/f C:\Users\depidsvy\AppData\Local\Cypress
del /q/f C:\Users\depidsvy\AppData\Local\Chromium\User Data\Default\Cache\Cache_Data
del /q/f C:\Users\depidsvy\AppData\Local\Composer\repo
del /q/f C:\Users\depidsvy\AppData\Local\conda\conda\Cache
del /q/f C:\Users\depidsvy\AppData\Local\Google\Chrome\User Data\Default\Cache\Cache_Data
del /q/f C:\Users\depidsvy\AppData\Local\Package Cache
del /q/f C:\Users\depidsvy\AppData\Local\pip\cache
del /q/f C:\Users\depidsvy\AppData\Local\Yarn\Cache
```
