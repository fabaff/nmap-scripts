# nmap NSE scripts
This project contains additional scripts to extend the default nmap
capabilities.

## Setup

Move or copy all the scripts you want to use to your nmap script directory
(eg. /usr/share/nmap/scripts/).

Or use [ansible](https://github.com/ansible/ansible) to install the scripts:

```bash
$ ansible-playbook nmap-scripts.yml -f 10
```

## Author
 * Fabian Affolter <fabian@affolter-engineering.ch>

## Licensing
All nmap scripts are licensed same as Nmap -- http://nmap.org/book/man-legal.html
Other things are licensed under GPLv2, for more details check COPYING.
