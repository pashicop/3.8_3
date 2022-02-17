# 3.8_3
# 1
```
route-views>sh ip route 195.182.130.34
Routing entry for 195.182.128.0/19, supernet
  Known via "bgp 6447", distance 20, metric 0
  Tag 6939, type external
  Last update from 64.71.137.241 4d04h ago
  Routing Descriptor Blocks:
  * 64.71.137.241, from 64.71.137.241, 4d04h ago
      Route metric is 0, traffic share count is 1
      AS Hops 3
      Route tag 6939
      MPLS label: none
route-views>sh bgp 195.182.130.34
BGP routing table entry for 195.182.128.0/19, version 305291131
Paths: (22 available, best #22, table default)
  Not advertised to any peer
  Refresh Epoch 1
  701 5511 12389 12389 12389 50509 6858
    137.39.3.55 from 137.39.3.55 (137.39.3.55)
      Origin IGP, localpref 100, valid, external
      path 7FE170166F68 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  53767 6939 50509 6858
    162.251.163.2 from 162.251.163.2 (162.251.162.3)
      Origin IGP, localpref 100, valid, external
      Community: 53767:2000
      path 7FE159B1F328 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3549 3356 9002 6858
    208.51.134.254 from 208.51.134.254 (67.16.168.191)
      Origin IGP, metric 0, localpref 100, valid, external
      Community: 3356:2 3356:22 3356:100 3356:123 3356:503 3356:903 3356:2067 35                                                                                                                                                             49:2581 3549:30840
      path 7FE15AFCC418 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3356 9002 6858
    4.68.4.46 from 4.68.4.46 (4.69.184.201)
      Origin IGP, metric 0, localpref 100, valid, external
      Community: 3356:2 3356:22 3356:100 3356:123 3356:503 3356:903 3356:2067
      path 7FE18BF147E8 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  8283 1299 20485 6858
    94.142.247.3 from 94.142.247.3 (94.142.247.3)
      Origin IGP, metric 0, localpref 100, valid, external
      Community: 1299:30000 8283:1 8283:101
      unknown transitive attribute: flag 0xE0 type 0x20 length 0x18
        value 0000 205B 0000 0000 0000 0001 0000 205B
              0000 0005 0000 0001
      path 7FE09280A2D8 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  4901 6079 9002 6858
    162.250.137.254 from 162.250.137.254 (162.250.137.254)
      Origin IGP, localpref 100, valid, external
      Community: 65000:10100 65000:10300 65000:10400
      path 7FE119C29230 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  57866 9002 6858
    37.139.139.17 from 37.139.139.17 (37.139.139.17)
      Origin IGP, metric 0, localpref 100, valid, external
      Community: 9002:0 9002:64667
      path 7FE1255C5790 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  852 6939 50509 6858
    154.11.12.212 from 154.11.12.212 (96.1.209.43)
      Origin IGP, metric 0, localpref 100, valid, external
      path 7FE0AC0FD5F0 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  20912 6939 50509 6858
    212.66.96.126 from 212.66.96.126 (212.66.96.126)
      Origin IGP, localpref 100, valid, external
      Community: 20912:65016
      path 7FE132241778 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3303 20485 6858
    217.192.89.50 from 217.192.89.50 (138.187.128.158)
      Origin IGP, localpref 100, valid, external
      Community: 3303:1004 3303:1006 3303:1030 3303:3056 20485:10078 20485:65100
      path 7FE16480A130 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3333 9002 6858
    193.0.0.56 from 193.0.0.56 (193.0.0.56)
      Origin IGP, localpref 100, valid, external
      path 7FE1507E9A98 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  7018 1299 20485 6858
    12.0.1.63 from 12.0.1.63 (12.0.1.63)
      Origin IGP, localpref 100, valid, external
      Community: 7018:5000 7018:37232
      path 7FE11309E198 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3561 3910 3356 9002 6858
    206.24.210.80 from 206.24.210.80 (206.24.210.80)
      Origin IGP, localpref 100, valid, external
      path 7FE0F5871030 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  1351 6939 50509 6858
    132.198.255.253 from 132.198.255.253 (132.198.255.253)
      Origin IGP, localpref 100, valid, external
      path 7FE100340548 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  20130 6939 50509 6858
    140.192.8.16 from 140.192.8.16 (140.192.8.16)
      Origin IGP, localpref 100, valid, external
      path 7FE125273FC8 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  1221 4637 9002 6858
    203.62.252.83 from 203.62.252.83 (203.62.252.83)
      Origin IGP, localpref 100, valid, external
      path 7FE13ADE57C8 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  101 6939 50509 6858
    209.124.176.223 from 209.124.176.223 (209.124.176.223)
      Origin IGP, localpref 100, valid, external
      Community: 101:20300 101:22100
      path 7FE0F231FB90 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  19214 3257 9002 6858
    208.74.64.40 from 208.74.64.40 (208.74.64.40)
      Origin IGP, localpref 100, valid, external
      Community: 3257:8791 3257:50001 3257:53100 3257:53101 65535:65284
      path 7FE131892850 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 2
  2497 20485 6858
    202.232.0.2 from 202.232.0.2 (58.138.96.254)
      Origin IGP, localpref 100, valid, external
      path 7FE1318886D0 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  49788 6939 50509 6858
    91.218.184.60 from 91.218.184.60 (91.218.184.60)
      Origin IGP, metric 0, localpref 100, valid, external
      Community: 49788:1000
      path 7FE11F6AA530 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  3257 9002 6858
    89.149.178.10 from 89.149.178.10 (213.200.83.26)
      Origin IGP, metric 10, localpref 100, valid, external
      Community: 3257:8052 3257:50001 3257:54900 3257:54901 65535:65284
      path 7FE0E47EECA8 RPKI State not found
      rx pathid: 0, tx pathid: 0
  Refresh Epoch 1
  6939 50509 6858
    64.71.137.241 from 64.71.137.241 (216.218.252.164)
      Origin IGP, localpref 100, valid, external, best
      path 7FE0F1DC6778 RPKI State not found
      rx pathid: 0, tx pathid: 0x0
```
# 2
```
pashi@pashi-ub2004-test:/etc/network$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host
       valid_lft forever preferred_lft forever
2: ens160: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 00:0c:29:ab:0f:7e brd ff:ff:ff:ff:ff:ff
    altname enp3s0
    inet 10.1.4.94/24 brd 10.1.4.255 scope global dynamic noprefixroute ens160
       valid_lft 86147sec preferred_lft 86147sec
    inet6 fe80::8042:b022:3eda:816f/64 scope link noprefixroute
       valid_lft forever preferred_lft forever
4: dummy5: <BROADCAST,NOARP,UP,LOWER_UP> mtu 1500 qdisc noqueue state UNKNOWN group default qlen 1000
    link/ether be:54:d9:53:7e:62 brd ff:ff:ff:ff:ff:ff
    inet 10.10.10.1/24 scope global dummy5
       valid_lft forever preferred_lft forever
    inet6 fe80::bc54:d9ff:fe53:7e62/64 scope link
       valid_lft forever preferred_lft forever
```
```
pashi@pashi-ub2004-test:/etc/network$ sudo ip route add 10.10.55.0/24 via 10.1.4.6
pashi@pashi-ub2004-test:/etc/network$ ip route
default via 10.1.4.6 dev ens160 proto dhcp metric 100
10.1.4.0/24 dev ens160 proto kernel scope link src 10.1.4.94 metric 100
10.10.10.0/24 dev dummy5 proto kernel scope link src 10.10.10.1
10.10.55.0/24 via 10.1.4.6 dev ens160
169.254.0.0/16 dev ens160 scope link metric 1000
```
# 3
```
pashi@pashi-ub2004-test:/etc/network$ ss -tln
State                       Recv-Q                      Send-Q                                            Local Address:Port                                             Peer Address:Port                      Process
LISTEN                      0                           4096                                              127.0.0.53%lo:53                                                    0.0.0.0:*
LISTEN                      0                           128                                                     0.0.0.0:22                                                    0.0.0.0:*
LISTEN                      0                           5                                                     127.0.0.1:631                                                   0.0.0.0:*
LISTEN                      0                           128                                                        [::]:22                                                       [::]:*
LISTEN                      0                           5                                                         [::1]:631                                                      [::]:*
```
22 порт - ssh  
53 порт - dns
# 4
```
pashi@pashi-ub2004-test:/etc/network$ ss -uan
State                       Recv-Q                      Send-Q                                              Local Address:Port                                            Peer Address:Port                     Process
UNCONN                      0                           0                                                   127.0.0.53%lo:53                                                   0.0.0.0:*
ESTAB                       0                           0                                                10.1.4.94%ens160:68                                                  10.1.4.4:67
UNCONN                      0                           0                                                         0.0.0.0:631                                                  0.0.0.0:*
UNCONN                      0                           0                                                         0.0.0.0:41626                                                0.0.0.0:*
UNCONN                      0                           0                                                         0.0.0.0:5353                                                 0.0.0.0:*
UNCONN                      0                           0                                                            [::]:42572                                                   [::]:*
UNCONN                      0                           0                                                            [::]:5353                                                    [::]:*
```
53 порт - dns  
68 порт - dhcp
# 5
![image](https://user-images.githubusercontent.com/97126500/154539343-836010d9-254d-4421-bd8e-7b091fffcb97.png)



