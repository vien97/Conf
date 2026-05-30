# Conf

Configuration repository for Surge node proxy settings.

## Description

This repository contains configuration files for Surge, including node proxy configurations and network settings.

## Node Proxy Configuration

Surge supports various types of proxy nodes that can be configured for routing traffic:

### Supported Proxy Types

- **HTTP/HTTPS**: Standard HTTP and HTTPS proxies
- **SOCKS5**: SOCKS5 proxy protocol
- **Shadowsocks**: Shadowsocks encryption protocol
- **Vmess**: Vmess protocol support
- **Trojan**: Trojan protocol support

### Example Proxy Configuration

```
[Proxy]
Direct = direct
ProxyHTTP = http, 192.168.1.1, 8080
ProxySocks5 = socks5, 192.168.1.1, 1080
```

## Installation

```bash
git clone https://github.com/Vien97/conf.git
cd conf
```

## Usage

1. Import the configuration files into your Surge application
2. Configure proxy nodes according to your network setup
3. Set routing rules to use the appropriate proxy nodes

## File Structure

- `surge.conf` - Main Surge configuration file
- `proxy.conf` - Proxy node definitions
- `rules.conf` - Routing rules

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
