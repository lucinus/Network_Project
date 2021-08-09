### README.md ###



* 네트워크 프로젝트 *

[구축 개요]
본사와 지사, 인수한 A회사 간 통신 가능한 망 굿헝

[구축 목적]
논리적으로 브로드캐스트 도메인을 나눠 LAN 구간 성능 향상
이중화를 통한 네트워크 장애 발생시 피해 최소화
여러 보안 기능을 통한 보안성 강화
QOS를 통한 대역폭 및 품질 보장
SSH를 사용하여 원격 접속을 통한 라우터 관리 기능
공중 사설 네트워크 망 구성

적용 기술
- Switch : VLAN, RSTP, MSTP, Etherchannel, L3 Switch, Port-Security, Storm-Control, BPDU Guard, SPAN
- Router : OSPF, PBR, BGP, VRRP, GLBP, DHCP, NAT, ACL, AAA, SSH, QOS(LLQ, WRED) 
- Security : GRE Tunnel, IPSec VPN