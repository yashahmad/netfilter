
![alt text](https://raw.githubusercontent.com/ivanlmj/PyCaptive/master/app/static/pycaptive_logo.png)

Authenticated Internet Access for Open Wifi Hotspots.

**Netfilter** is an authentication service for Open WiFi Hotspots, working as a Captive Portal. That means: users who wish to have Internet Access through an Open Wifi Hotspot which is backed by PyCaptive, must authenticate to open a session, which is based on Username, IP Address and Expire Time, according with Login Time.  **Additionally**, PyCaptive performs the authentication role for Wired networks and for network servers that have Transparent Proxy service, since that Proxies in Transparent mode, are not capable to provide authentication.

### Characteristics
- Front-end: HTML, CSS and Jinja2
- Back-end: Python, Flask, MongoDB, IPTABLES

### Requirements
- Server: 3.0Ghz; RAM 2Gb; HDD 32Gb; 2 NICs (100/1000Mbps); NIX-Like OS (Debian/Ubuntu)
- Python v3.5
- PIP3 Packages ([Flask, Gunicorn WSGI...]
- MongoDB v3.4
- Nginx v1.6
- IPTABLES v1.4
- Routing Configuration for traffic between NICs (IPTABLES)
- Traffic Redirection for Authenticated and Non-Authenticated Users (IPTABLES)

