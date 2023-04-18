Redirect connections from different ports at one ipv4 address to unique random ipv6 address from \64 subnetwork. Based on 3proxy

# The script not working. Need a maintainer
# The script not working. Need a maintainer
# The script not working. Need a maintainer


![cover](cover.svg)

## Requirements
- Centos 7
- Ipv6 \64

## Installation

1. `wget https://raw.githubusercontent.com/quachcodon/ipv4-ipv6-proxy/main/setup.sh && chmod +x setup.sh && bash setup.sh`

1. After installation dowload the file `proxy.zip`
   * File structure: `IP4:PORT:LOGIN:PASS`
   * You can use this online [util](http://buyproxies.org/panel/format.php
) to change proxy format as you like

## Test your proxy

Install [FoxyProxy](https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/) in Firefox
![Foxy](foxyproxy.png)

Open [ipv6-test.com](http://ipv6-test.com/) and check your connection
![check ip](check_ip.png)

