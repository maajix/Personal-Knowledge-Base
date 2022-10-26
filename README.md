# Useful Commands (General)
| **Command**                                                                                               | **Description**                                |
| --------------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| `locate <path>`                                                                                           | Find files in any directory                    |
| `ssh-keygen -t rsa`                                                                                       | Generate key pair (SSH)                        |
| `which <programm_name>`                                                                                   | Finds the path to a given program if it exists |
| `openssl req -x509 -out server.pem -keyout server.pem -newkey rsa:2048 -nodes -sha256 -subj '/CN=server'` | Create a self-signed certificate               |
| `gunzip -S .zip <file>`                                                                                   | Unzip a file                                   |
| `sudo -l`                                                                                                 | Check missconfigured binarys                                               |

# Useful Commands (NMAP)
| Command                                            | Description                                              |
| -------------------------------------------------- | -------------------------------------------------------- |
| `tcpdump -i tun0 host <host_ip>`                   | Can display additional information nmap doesn't show     |
| `nmap <host_ip> -Pn -n -disable-arp-ping -sV -sS ` | Stealth nmap scan which enumerates service versions      |
| `nmap --source-port <port>`                        | Can bypass miss configured firewalls by imitating a port |
| `xsltproc <xml_file> -o <html_file>`               | Export nmap scan to HTML file                            |

# Useful Commands (Services)
| Command              | Description             |
| -------------------- | ----------------------- |
| `nc -nv <ip> <port>` | Interact with a service |
| `telnet <ip> <port>` | Interact with a service |
| `ftp <ip>`           | Interact with ftp service   | 


