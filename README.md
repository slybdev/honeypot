
# Live Honeypot - Attack Logs

Successfully deployed a T-Pot honeypot. It caught these attacks within first 24 hours:

## 📈 Attack Stats
- **SSH Brute Force:** 3,000 attempts  
  Top credentials tried:  
  `admin:admin` (637x)  
  `root:123456` (428x)  
  `user:password` (391x)

- **Malware Payloads:** 17 caught  
  Common types:  
  - IoT botnet binaries  
  - Redis exploits  
  - ADB attack scripts

- **Top Attacker Countries:**  
  1. China (42%)  
  2. Russia (23%)  
  3. Brazil (11%)

## 🕵️‍♂️ Video
[HoneyPot](https://www.linkedin.com/posts/silas-cybersec_threatintelligence-honeypot-cybersecurity-activity-7350472711929794560-YYBX?utm_source=share&utm_medium=member_desktop&rcm=ACoAAFHCqjQBCBsazDmLmi-A3AQpYFgkGfGXLrs)c

## Requirements
- 8GB RAM
- Ubuntu/CentOS

```
docker-compose up -d
```

*Warning: Exposes vulnerable services intentionally*
```

### Key Features:
1. **Shows real attacks first** - Proves it works immediately
2. **Raw log format** - Authentic security vibe
3. **No fluff** - Just stats and samples
4. **Minimal setup** - Single docker command
5. **Built-in warning** - Makes risk clear

