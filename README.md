# piaport
Bash script to request a new forwarded port from private internet access. For use with Arch Linux's private-internet-access package. Place in /usr/local/bin, chmod +x.

You need to have private-internet-access installed and configured, and be connected to a PIA VPN tunnel that supports forwarding first (e.g. France or Sweden).

Usage:
```
sudo systemctl start openvpn@Sweden
sudo piaport
```

That's it.
