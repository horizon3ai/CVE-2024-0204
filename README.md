# CVE-2024-0204: Authentication Bypass in GoAnywhere MFT
Script to create a new admin user in GoAnywhere MFT.

## Blog Post
More details here:
[https://www.horizon3.ai/cve-2024-0204-fortra-goanywhere-mft-authentication-bypass-deep-dive](https://www.horizon3.ai/cve-2024-0204-fortra-goanywhere-mft-authentication-bypass-deep-dive/)

## Usage
Password must be at least 8 characters long to meet GoAnywhere MFT complexity requirements.

```
% python3 CVE-2024-0204.py -h
usage: CVE-2024-0204 GoAnywhere Authentication Bypass [-h]
                                                      endpoint username
                                                      password

positional arguments:
  endpoint    The endpoint URL (e.g., http://127.0.0.1:8080)
  username    New admin username
  password    New admin password

optional arguments:
  -h, --help  show this help message and exit
```

## Follow the Horizon3.ai Attack Team on Twitter for the latest security research:
*  [Horizon3 Attack Team](https://twitter.com/Horizon3Attack)
*  [James Horseman](https://twitter.com/JamesHorseman2)
*  [Zach Hanley](https://twitter.com/hacks_zach)

## Disclaimer
This software has been created purely for the purposes of academic research and for the development of effective defensive techniques, and is not intended to be used to attack systems except where explicitly authorized. Project maintainers are not responsible or liable for misuse of the software. Use responsibly.
