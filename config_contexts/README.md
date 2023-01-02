Local config context of the devices

You can add your own additional configs by using

additional:
 - config: >
    extra config for pod1r1

to add the config globally or by 

interfaces:
   - name: Loopback0
     config:
       - addition config

to add a config to an interface.

