# Luxer One locker codes page for TRMNL

A single static page that the Luxer One TRMNL plugin links to from its on-screen QR code.
Scanning the code opens this page on your phone with each waiting package's access code and locker QR code.

## Privacy

- The codes travel in the part of the link after `#`, which browsers never send to a server.
- The page is one file with no external requests; its Content-Security-Policy blocks all network access.
- Codes are kept only in your phone's browser, removed from the address bar after loading, and erased after 7 days.

Anyone who can scan the TRMNL screen can read the codes, the same as anyone who can read the numbers on it.

## Credits

QR codes are drawn with [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) by Kazuhiko Arase (MIT), inlined in `index.html`.

Unofficial; not affiliated with Luxer One.
