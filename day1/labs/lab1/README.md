# Threat hunting - Lab1
* Date: 2020/7/27 afternoon
* Target: 找到攻擊者控制的機器 IP

一般在找很大的 pcap，會想辦法鎖定目標，所以會從 filename 下手，所以 filter 可以下 `smb.fn == "*.exe" || smb.fn == "*.dll"`

* ref: https://www.itread01.com/content/1547260384.html
* sol: 192.168.137.21
