# Backhaul Premium

Backhaul Premium - A powerful reverse tunnel and proxy management script for Linux servers.

## Features

- TCP and UDP tunnel support
- Multiplexer (Mux) support for optimized connections
- TLS/WSS/WS transport protocols
- Automatic certificate generation
- iptables-based port forwarding
- Easy service management (start/stop/restart/status)
- Multi-port configuration
- Server and Client mode support

## Quick Install & Run

Run the following command on your server:

```bash
bash <(curl -sSL https://raw.githubusercontent.com/logi443/backhaul_p/main/backhaul.sh)
```

## Requirements

- Linux server (Ubuntu/Debian/CentOS)
- Root access
- `curl` and `jq` installed (script will auto-install `jq` if missing)

## Usage

After running the install command, the interactive menu will guide you through:

1. **Create a new configuration** - Set up server or client tunnels
2. **View existing configurations** - List and manage active configs
3. **Manage services** - Start, stop, restart, or check status
4. **Update core** - Download the latest Backhaul binary
5. **Uninstall** - Remove all configurations and services

## Architecture Support

- x86_64 (AMD64)

## License

For personal and educational use only.
