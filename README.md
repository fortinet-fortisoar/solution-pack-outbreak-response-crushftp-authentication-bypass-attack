# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

FortiGuard Labs has identified ongoing and persistent attack attempts in the wild that are aimed at exploiting CVE-2025-31161, which is an authentication bypass vulnerability found in CrushFTP file transfer server. If successfully exploited, this vulnerability could allow attackers to gain administrative access to the application, representing a significant risk to enterprise environments. 

 The **Outbreak Response - CrushFTP Authentication Bypass Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.0.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/crushftp-authentication-bypass) contains information about the outbreak alert **Outbreak Response - CrushFTP Authentication Bypass Attack**. 

## Background: 

An attacker may take advantage of this vulnerability by sending a specifically crafted HTTP request to the CrushFTP server. If exploited, this vulnerability could result in complete system compromise. Attackers would be able to impersonate users, execute administrative actions, access sensitive information, and upload harmful content.

This vulnerability is remotely exploitable, and a proof-of-concept (PoC) exploit is now publicly accessible. This situation heightens the risk of swift adoption by threat actors, including ransomware groups that have previously targeted other Managed File Transfer (MFT) platforms such as MOVEit Transfer and Cleo MFT.

The versions affected range from 10.0.0 to 10.8.3 and from 11.0.0 to 11.3.0. Users are strongly advised to promptly update to versions 10.8.4 or 11.3.1 and later. 

## Announced: 

FortiGuard Labs recommends users to apply the fix provided by the vendor and follow any instructions as mentioned on the vendor's advisory if not already done.  

## Latest Developments: 

April 8, 2025: FortiGuard Labs released a Threat Signal.
https://www.fortiguard.com/threat-signal-report/6072/crushftp-authentication-bypass

April 7, 2025: CISA Adds CVE-2025-31161 to its Known Exploited Vulnerability to Catalog.
https://www.cisa.gov/news-events/alerts/2025/04/07/cisa-adds-one-known-exploited-vulnerability-catalog

March 21, 2025: CrushFTP released an advisory.
https://www.crushftp.com/crush11wiki/Wiki.jsp?page=Update 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|