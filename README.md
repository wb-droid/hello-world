# hello-world
hello
hello to git hub

#ifcfg-ens34
DEVICE="ens34"
USERCTL="no"
TYPE="Ethernet"
BOOTPROTO="none"
ONBOOT="yes"
IPADDR="192.251.254.254"
PREFIX="24"
PEERDNS="no"
DEFROUTE="no"
MTU="1500"
NM_CONTROLLED="no"
ZONE=trusted


[root@cortx-ova ~]# cat /etc/sysconfig/network-scripts/ifcfg-ens33
DEVICE="ens33"
USERCTL="no"
TYPE="Ethernet"
BOOTPROTO="dhcp"
ONBOOT="yes"
DEFROUTE="no"
NM_CONTROLLED="no"
ZONE=public-data-zone

DEVICE="ens32"
HWADDR="08:00:27:d8:a1:3b"
USERCTL="no"
TYPE="Ethernet"
BOOTPROTO="dhcp"
ONBOOT="yes"
DEFROUTE="yes"
NM_CONTROLLED="no"
ZONE=public
