
### REQUIRED BEFORE INSTALLATION
<pre><code>sudo apt update && sudo apt upgrade -y && sudo timedatectl set-timezone Africa/Nairobi && sudo apt install curl wget git sudo -y
</code></pre>

### INSTALL SCRIPT
<pre><code>apt update -y && apt install -y wget curl jq screen && wget -q https://raw.githubusercontent.com/etunnelvpn/vpnscript/main/setup.sh && chmod +x setup.sh && ./setup.sh
</code></pre>

### UPDATE COMMAND
<pre><code>wget -q https://raw.githubusercontent.com/etunnelvpn/vpnscript/main/update.sh && chmod +x update.sh && ./update.sh</code></pre>

### TESTED ON OS
- UBUNTU 20.04
- UBUNTU 22.04
- UBUNTU 24.04
- DEBIAN 10
- DEBIAN 11
- DEBIAN 12

### FEATURES
- 1GiB Swap Installation
- Dynamic installation process
- Server tuning profile
- Xray Core
- Fail2ban protection
- Auto block ads by default
- Auto clear logs every 3 minutes
- Auto delete expired accounts
- User account details
- Telegram bot panel
- SlowDNS support
- NoobzVPN protocol
- UDP Custom
- OpenVPN SSL/TCP/UDP
- SSH WebSocket & SSL

### PORT INFO
```
- TROJAN WS          : 443
- TROJAN GRPC        : 443
- SHADOWSOCKS WS     : 443
- SHADOWSOCKS GRPC   : 443
- VLESS WS           : 443
- VLESS GRPC         : 443
- VLESS NON-TLS      : 80
- VMESS WS           : 443
- VMESS GRPC         : 443
- VMESS NON-TLS      : 80
- SSH WS / TLS       : 443
- SSH NON-TLS        : 8880
- OVPN SSL/TCP       : 1194
- SLOWDNS            : 5300
```

### CLOUDFLARE SETTINGS
```
- SSL/TLS            : FULL
- SSL/TLS Recommender: OFF
- gRPC               : ON
- WebSocket          : ON
- Always Use HTTPS   : OFF
- Under Attack Mode  : OFF
```

### CONTACT
- Telegram : t.me/emmkash
- WhatsApp : wa.me/254112735877
