#lokman5437

# 1st
```
apt update -y && apt upgrade -y && apt full-upgrade -y

```

# 2nd
```
echo -e "[ Info ] Download setup file" && sysctl -w net.ipv6.conf.all.disable_ipv6=1 &> /dev/null && sysctl -w net.ipv6.conf.default.disable_ipv6=1 &> /dev/null && apt update &> /dev/null && apt install -y bzip2 gzip coreutils screen curl wget tcpdump dsniff grepcidr dnsutils &> /dev/null && wget https://raw.githubusercontent.com/shopeevpn/lokman5437/main/setup.sh &> /dev/null && chmod +x setup.sh && "/root/setup.sh"

```
