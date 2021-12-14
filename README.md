# CEH-Practical-Notes

14 Dec 2019   | @mrrobot1o1

## Foot Printing and Reconnaissance

YouTube Date Viewer

[Citizenevidence](https://citizenevidence.amnestyusa.org/)

[NAPALM FTPS](https://www.searchftps.net/)

**theHarvester**

theHarverster -d example.com -l 200 -b linkedin

**sherlock**

sherlock.py Vikas Yadav


[Followerwonk](https://followerwonk.com/)


**Custom Wordlist Genrator by [Kali Linux]**

cewl -d 2 -m 5 -w docswords.txt https://example.com


**Email Header Analysis**

EmailTrackerPro

**WHOIS**
whois
arein.net


**nslookup**
set type=a
set type=cname

You can use kloth.net OR yougetsignal.com ad alternative

**recon-ng**
```sh
> marketplace install all
> modules search
> workspaces  create Test
> workspaces list
> db insert domains
:example.com
> modules load brute_hots
```
**usufy.py**

usufy.py -name mrrobo1o1 -p twitter

**domainfy.py**

domainfy.py -n tesla -t all > -t = tld

**billcipher.py**


hping3 10.10.10.10. --udp --rand-source --data 500


nmap -Pn -sS -A -oX test 10.10.10.10/24


**Netbios Enumeration**

nmap -sV -v --script nbstat.nse 10.10.10.10

snmp-check 10.10.10.10


**DNS Recon**

dnsrecon -f example.com -z


**RPC Info**

### HackerSploit NetBIOS and SMB Enumration

137 netbios [network basic input and output system]

139,445 smb   [system massege block]

sbtstat -A 10.10.10.10

nbtscan  [alternative on linux]

nbtscan -r -v 10.10.10.10

smbclient -L 10.10.10.10

smbmap -H 10.10.10.10
