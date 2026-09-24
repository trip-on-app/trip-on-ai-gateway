# Trip ON AI Gateway Discovery

This repository stores only public discovery metadata for Trip ON local AI gateway tunnels.
It must never contain gateway tokens, passwords, API keys, or other secrets.

`gateway.json` is updated whenever a PC receives a new Cloudflare Quick Tunnel URL.
The Trip ON production Worker reads this fixed GitHub URL and falls back to its existing Worker secrets if discovery is unavailable.
