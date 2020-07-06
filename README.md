# SMBGhost (CVE-2020-0796) and SMBleed (CVE-2020-1206) Scanner

(c) 2020 ZecOps, Inc. - https://www.zecops.com - Find Attackers' Mistakes  
Intended only for educational and testing in corporate environments.  
ZecOps takes no responsibility for the code, use at your own risk.  
Please contact sales@ZecOps.com if you are interested in agent-less DFIR tools for Servers, Endpoints, and Mobile Devices to detect SMBGhost, SMBleed and other types of attacks automatically.

## Usage

`SMBGhost-SMBleed-scanner.py target_ip`

The scanner will report whether the target machine is vulnerable to SMBGhost and/or SMBleed.

**Note:** The scanner will crash the target machine if it's running an unpatched Windows 10 version 1903. The crash is caused by a null dereference bug which is fixed by the **KB4512941** update.

## References

* [Vulnerability Reproduction: CVE-2020-0796 POC - ZecOps Blog](https://blog.zecops.com/vulnerabilities/vulnerability-reproduction-cve-2020-0796-poc/)
* [SMBleedingGhost Writeup: Chaining SMBleed (CVE-2020-1206) with SMBGhost - ZecOps Blog](https://blog.zecops.com/vulnerabilities/smbleedingghost-writeup-chaining-smbleed-cve-2020-1206-with-smbghost/)
* [CVE-2020-0796 - Microsoft Security Response Center](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-0796)
* [CVE-2020-1206 - Microsoft Security Response Center](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2020-1206)
