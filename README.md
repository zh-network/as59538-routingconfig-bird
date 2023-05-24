# ZH-BUSINESS NETWORK BIRD CONFIG
<img src="zhnetremovebg-cut.png" />
  
## ZH BUSINESS NET (AS59538) BGP Communities [FOR PUBLIC SERVICE]
#### Community list for ZHNET customers
6939  = Hurricane Electric  

#### 59538, 1 ZHNET-BUSINESS-LONDON-UK  
<strong>No advertise communities</strong>  
666:x where is the ASN of the peer your route will not be advertised to at all   

## ZH BUSINESS NET (AS59538) BGP Communities [FOR INTERAL SERVICE]  
  
#### BGP Pref
upstream: bgp_local_pref = 300;  
peer: bgp_local_pref = 500;  
downstream: upstream: bgp_local_pref = 900;  
  
#### OSPF Node ID
LON1-CORE = 1001  
LON1-EDGE(Temp) = 1002  

#### IBGP IP CIDR & Range  
IPv6 Anycast Prefix 2a0f:7801:ffff::/48    
Anycast Node IPs : 2a0f:7801:ffff:location::nodeid/128  

LON1-CORE = 01  

#### 59538, 1 ZHNET-BUSINESS-LONDON-UK  
59538, 1, 65001 From Downstreams  
59538, 1, 65002 From Peers  
59538, 1, 65003 From Upstreams  
  
