# SuperRare Stored XSS 0day
A stored XSS vulnerability I discovered in SuperRare in Nov 2022 that SuperRare refuses to fix. This was reported in November 2022 and SuperRare's 90 day grace period expired 8 months ago. SuperRare's attorney states that this vulnerability isn't going to be fixed since it's "out of scope". This is despite the fact that the exploit can be adjusted to steal arbitrary users' funds and NFTs. If SuperRare explicitly said they won't fix this and is actively refusing to protect their users, then I will with public disclosure.

The report and payload is not the cleanest but if you understand what's happening you can figure out the right adjustments to make this a full attack.

Files:
* Report - step-by-step guide to exploit the vulnerability
* XSS.gif - POC attack vector
* Exploit.txt - the malicious JS payload that steals funds
* Video POC - https://drive.google.com/file/d/15hN4lKZVJ2xds7qzpwQhsmkG_o31kKtd/view?usp=share_link
