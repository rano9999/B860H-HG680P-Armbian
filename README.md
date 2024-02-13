# B860H-HG680P-Armbian
User Default : root  
Password : 1234  

## Buat Bootable  
Extract  
Buat bootable dengan bootable maker ([Rufus](https://rufus.ie/) atau [balenaEtcher](https://www.balena.io/etcher/))  
Copy file dtb ke /dtb/armbian  

note : dtb sudah disesuaikan untuk RAM 2gb, untuk ram 1gb tidak perlu copy dtb

## Boot Dari STB
Pasang MicroSD/FD ke STB, pastikan STB sudah Root.
Buka Terminal Emulator, ketik perintah berikut:
reboot update

Tunggu sampai Armbian selesai loading dan meminta untuk membuat Password root baru.

## Setting Armbian  
Setting WiFi, jam dll  
Login Armbian -> input command
```yaml
armbian-config
```

## Maximize penggunaan SDcard atau Flashdisk  
Perinatah ini bertujuan untuk menggunakan seluruh kapasitas yang tersedia sebagai ROOT  
Login Armbian -> input command
```yaml
armbian-tf
```

## Docker
Install Docker   
Login Armbian -> input command
```yaml
armbian-docker
```
  
  
Terimakasih untuk [ophub](https://github.com/ophub) yang telah menyediakan file iso armbian untuk amlogic s905x
