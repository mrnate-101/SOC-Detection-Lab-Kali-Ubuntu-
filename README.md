# SOC Detection Lab – Attacker vs Defender

Real home lab simulating reconnaissance and brute-force attacks → detected in logs.

**Target (Victim)** → Ubuntu Server (192.168.64.3)  
**Attacker** → Kali Linux (192.168.64.4)

### Attacks Performed
- Full port scan + OS detection (`nmap -A`)
- Web vulnerability scan (`nikto`)
- SSH connection attempts

### Detection Evidence
Real indicators captured in `/var/log/auth.log`

### Screenshots
![Nmap Full Scan](screenshots/nmap.png)
![Nikto Scan](screenshots/nikto.png)
![SSH Attack Logs](screenshots/auth-log.png)

**Skills Demonstrated**  
Network reconnaissance · Vulnerability scanning · Log analysis · Incident detection
