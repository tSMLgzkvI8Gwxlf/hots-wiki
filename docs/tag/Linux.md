# <i class="fab fa-ubuntu"></i> Ubuntu / Debian 下载应用
我们相信您不需要详细教程即可进行下载操作。

Debian / Ubuntu (64-bit) 下载
```
sudo apt install -y wget apt-transport-https

sudo wget -O /usr/share/keyrings/riot-im-archive-keyring.gpg https://packages.riot.im/debian/riot-im-archive-keyring.gpg

echo "deb [signed-by=/usr/share/keyrings/riot-im-archive-keyring.gpg] https://packages.riot.im/debian/ default main" 

sudo tee /etc/apt/sources.list.d/riot-im.list

sudo apt update

sudo apt install element-desktop
```