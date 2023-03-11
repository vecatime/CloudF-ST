# CloudF-ST
**2023 March UPDATE**: From a technical point of view, server access via VPN servers like V2ray via CDN seems reasonable. One of the powerful and free CDN providers is Cloudflare. If you want to connect to the fastest Cloudflare server, you can use iSH after installing the Linux code runner, for example on IOS devices.

After downloading and installing, open it, and you will see the familiar Linux system at this time! The next step is the same as the download and run steps on the Linux system.

## Install CloudflareST
1. Create Directory 
```bash
mkdir CloudflareST
```
Enter the folder (for subsequent updates, you only need to enter the folder)

```bash
cd CloudflareST

```
Download the CloudflareST

```bash
wget -N https://github.com/XIU2/CloudflareSpeedTest/releases/download/v2.2.2/CloudflareST_linux_386.tar.gz
```

unzip 

```bash
tar -zxf CloudflareST_linux_386.tar.gz
```

grant execute permission

```bash
chmod +x CloudflareST
```


```bash
sudo apt install docker-ce
```
2. run CloudflareST

run (without arguments)

```bash
./CloudflareST
```
run (example with parameters)

```bash
./CloudflareST -dd -tll 90
```


Thank you very much for your attention and precious time spent reading this article.


## More
The script is based on [here](https://github.com/XIU2/CloudflareSpeedTest)
