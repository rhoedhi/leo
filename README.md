# leo

leo is an offensive information and vulnerability scanner.

## Features

Just supply a domain name to **leo** and it will automatically do the following for you:

- [x] Check and Bypass Cloudflare
- [x] Retrieve Server and Powered by Headers
- [x] Fingerprint the operating system of Web Server
- [x] Detect CMS (197+ CMSs are supported)
- [x] Launch WPScan if target is using Wordpress
- [x] Retrieve robots.txt
- [x] Whois lookup
- [x] Check if the target is a honeypot
- [x] Port Scan with banner grabbing
- [x] Dumps all kind of DNS records
- [x] Generate a map for visualizing the attack surface
- [x] Gather Emails related to the target
- [x] Find websites hosted on the same web server
- [x] Find hosts using google
- [x] Crawl the website for URLs having parameters
- [x] SQLi scan using online implemention of SQLMap (takes < 3 min.)
- [x] Basic XSS scanning

## Install

```bash
git clone https://github.com/rhoedhi/leo
cd leo
pip install -r requirements.txt
python leo.py
```


#### Contribute

If you want to contribute to this project, report any bugs you encounter and help me add more features to it.