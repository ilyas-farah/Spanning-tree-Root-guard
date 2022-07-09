# Spanning-tree-Root-guard
--------------------------
SW-1
------
spanning-tree vlan 1 priority 4096

SW-2
-----
spanning-tree vlan 1 priority 32768

SW-3
-----
spanning-tree vlan 1 priority 32768

Root Guard
------------
int range fa0/1-2
spanning-tree guard root
