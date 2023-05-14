# cutenews2.1.2_rce
RCE exploit for CuteNews 2.1.2 - CVE-2019-11447

CuteNews 2.1.2 is a vulnerable news management system which allows attackers to upload a malicious php script as a user avatar, and execute remote code.

I was familiar with this vulnerability from a CTF challenge I had completed. Although there is already a few exploits already available for this vulnerability, I figured it would be fun to make my own.

Credit to AkkuS, the security researcher responsible for finding the vulnerability: https://www.exploit-db.com/exploits/46698

## Usage

```
python CVE-2019-11447.py -h
usage: CVE-2019-11447.py [-h] url

CuteNews 2.1.2 RCE

positional arguments:
  url         The url of the target

options:
  -h, --help  show this help message and exit
```
