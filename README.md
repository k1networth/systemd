# systemd

``` sh
sudo apt-get update && sudo apt-get upgrade -y
wget --content-disposition https://www.noip.com/download/linux/latest
tar xf noip-duc_*.tar.gz
cd noip-duc_*/binaries
sudo apt-get install ./noip-duc_*_amd64.deb
rm noip-duc_*.tar.gz
sudo systemctl daemon-reload
sudo systemctl start noip-duc
sudo systemctl status noip-duc
sudo systemctl enable noip-duc
```
