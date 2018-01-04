## myip

Get the default IP address of the machine.
The one you are always after when you type ifconfig. 
The IP assigned to the interface that the default route belongs to

```
Syntax & Example Usage

  myip            Print the primary IP Address
  myip ip         Verbose, same as above cmd
  myip if         Print only the default interface name
  myip sm         Print only the subnet mask
  myip gw         Print only the default gateway IP
  myip all        Print all; ifname ipaddr mask gw
  myip help       Print this information

Command Line Options
  -v,--version:  Print Version Number
  -h,--help:     Alias for help
  -a,--all:      TODO: Print all configured IP addresses
  -l,--list:     TODO: Print all Interface Name and IPs, one per line 
  --cidr:        TODO: Show IP with CIDR subnet mask i.e. /24
  --csv:         TODO: Output in CSV format
```

## httphere

A quick and easy way to serve up files from a directory using a simple http server built into python

The script will detect the installed version of python and use it, prefering python3

```
Syntax & Example Usage

  httphere            Starts an http server listening on port 8000 serving files from pwd
  
```
