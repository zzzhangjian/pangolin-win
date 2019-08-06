# Pangolin-win
This is a windows client for [pangolin](https://github.com/xitongsys/pangolin).
It supports udp and ptcp protocol.

## Quick start
1. Configure the config.txt file. 
```json
{
    "role": "client",
    "server": "149.129.49.157:12345",
    "tun": "10.0.0.22/8",
    "dns": "8.8.8.8",
    "mtu": 1400,
    "protocol": "ptcp",
    "tokens": ["token01", "token02"]
}
```

2. Run the ```pangolin-win.exe``` as Administrator.
