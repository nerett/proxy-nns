# proxy-nns
Create network namespace for any aplication and connect it to socks proxy via virtual interface.

## Requirements
- `tun2socks`
- local socks proxy server

Script currently supports only `firewalld` (used in OpenSuse). In other cases you need to edit rules manually.

## Usage
Edit script (set your localhost socks server port and tun2socks path), then run:

```bash
proxy-nns <command>
```
