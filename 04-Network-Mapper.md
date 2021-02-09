## Commands

> nmap -sS -T2 192.168.1.44 -oN

- Scanning Options
- Timing Options
- Target(s)
- Output options

> host -t ns microsoft.com

> host -t mx microsoft.com

## Types of Scanning

- Network Scan
- Port Scan
- Service Scan
- OS Scan
- Vulnerability Scan

## Tools used for Scanning

- Nmap
- Zenmap
- Nessus vulnerability Scanner
- Nexpose

> nmap -T3 -sP 192.168.0.0/24

- Timing Options
- All live hosts

## Port Scan

> nmap -T4 -p 1-1000 192.168.0.106 

## Service / Version Scan

> nmap -T4 -sV 192.168.0.106

> nmap -sS -T4 -p 1-1000 192.168.0.1

> nmap -sT -T4 -p 1-1000 192.168.0.1

> nmap -sU -T4 -p 53 192.168.0.106

> nmap -sA -T4 -p 1-1000 192.168.0.106

## Store result in text file

> nmap -sA -T4 -p 1-1000 192.168.0.106 -oN /root/myfile/scan.txt

## Find OS of particular host

> nmap -T4 -O 192.168.0.106

MAC Address:
Aggressive OS guesses: 

## Aggressive Scan

> nmap -T4 -A 192.168.0.1 

## Firewall Scan

> nmap -T4 192.168.0.106 -Pn

> nmap -T4 192.168.0.106 -f

