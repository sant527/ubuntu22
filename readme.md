# Workaround for libssl issue on Ubuntu 22.04
https://forum.unity.com/threads/workaround-for-libssl-issue-on-ubuntu-22-04.1271405/

```
wget "http://security.ubuntu.com/ubuntu/pool/main/o/openssl1.0/libssl1.0.0_1.0.2n-1ubuntu5.10_amd64.deb"
wget "http://security.ubuntu.com/ubuntu/pool/main/o/openssl1.0/libssl1.0-dev_1.0.2n-1ubuntu5.10_amd64.deb"
sudo dpkg -i libssl1.0.0_1.0.2n-1ubuntu5.10_amd64.deb
sudo dpkg -i libssl1.0-dev_1.0.2n-1ubuntu5.10_amd64.deb 
```
