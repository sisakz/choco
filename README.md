# Install Choco (Powershell admin)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

# Install Choco packages

```
choco install -y --ignore-checksum totalcommander GoogleChrome vscode nodejs-lts yarn pnpm composer deepl docker-desktop figma git hosts.editor iTunes lenovo-thinkvantage-system-update microsoft-teams naps2 obs-studio php postman powertoys spotify vlc mysql-cli gh
```
