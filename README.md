# macrelatedread
 sudo networksetup -createnetworkservice Loopback lo0
(base) gokhansahin ~ $ sudo networksetup -setmanual Loopback 172.20.42.42 255.255.255.255
(base) gokhansahin ~ $ ifconfig lo0 alias 127.0.0.1
127.0.0.1 netmask 0xff000000
