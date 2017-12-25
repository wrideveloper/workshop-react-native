# Instalasi node js

## Pada windows
1. Silahkan download nodejs dari website resminya di [https://nodejs.org/en/](https://nodejs.org/en/)

2. Pilih versi **node js LTS (Recommend for most users)**

3. Seteleh selesai didownload, silahkan lakukan instalasi seperti biasa

## Pada linux (ubuntu)

1. update repository anda
```
sudo apt update
```

2. install paket nodejs dan npm
```
sudo apt install nodejs
```
```
sudo apt install npm
```

3. install build essential
```
sudo apt install build-essential
```

**note** : ubah **apt** menjadi **apt-get** apabila anda menggunakan ubuntu dengan versi dibawah 16.04


## Menggunakan version Manager

### Windows
1. Install [Choco Package Manager](https://chocolatey.org/) 
2. Buka cmd paste kode berikut
```
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```
3. Install version manager menggunakan choco
```
choco install nvm
```
4. Kemudian Install nodejs yang diinginkan
```
nvm install 9.3.0
```

### Linux
1. Download install script menggunakan curl
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
``` 
2. pastikan apakah nvm sudah terinstall
```
command -v nvm
```
3. Kemudian install nodejs yang diinginkan
```
nvm install 9.3.0
```