# Portscanner
Python script to scan open ports

usage: scanner.py 192.168.0.1

Python Based Fast port scanner

positional arguments:

  IPv4           host to scan

options:

  -h, --help     show this help message and exit
  
  -s, --start    starting port
  
  -e, --end      ending port
  
  -t, --thread   threads to use
  
  -V, --verbose  verbose output
  
  -v, --version  display version

Example: scanner.py -s 20 -e 30000 -t 500 -V 192.168.0.1
