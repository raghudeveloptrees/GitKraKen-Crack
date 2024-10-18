# GitKraKen-Crack
GitKraKen8.2.0-9.x cracking and use

## 破解要求环境
- Node.js Version>=12 LTS
- yarn
- GitKraKen v8.2.0-9.x

## gitkraken下载地址
[gitkraken](https://download.informer.com/win-1191574157-1b1c9f62-6084b40e-5a7f65fcf3e07bc817-a31562017cc669524-11273292-1079771430/gitkrakensetup.exe)

## Cracking steps

After downloading, you need to run and install the downloaded GitKraken (it will be automatically installed to AppData/Local/gitkraken9.x). After the installation is complete, gitkraken will automatically open, so you can just close it.。
### 2.Install yarn from npm
- npm install --global yarn
### 3.git clone https://github.com/qsshs/GitKraKen-Crack.git
- cd GitKraKen-Crack
- yarn install
- yarn build
- yarn gitcracken patcher


## Follow-up
### Block updates
Just add a line at the bottom of the hosts file in C:\Windows\System32\drivers\etc `127.0.0.1 release.gitkraken.com`
> Alternatively, you can directly delete update.exe in the AppData/Local/gitkraken directory to disable gitkraken from automatically updating.

### Start from the software itself instead of updating or installing the package
The gitkraken.exe in the AppData/Local/gitkraken/app-9.x/ directory is the real client.
