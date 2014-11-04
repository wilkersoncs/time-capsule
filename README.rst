vTimeCapsule - Apple File server recognized as TimeMachine drive
=============================================

TurnKey Linux Core appliance modified to accept the Apple File storage Protocol (AFP) and also recognized by the Apple TimeMachine client as a TimeCapsule. 

vTimeCapsule includes all the standard features in `TurnKey Core`_, and on
top of that:

- Support for Apple File storage Protocol (AFP)
- Recognized by the Apple TimeMachine client as a TimeCapsule
- Potentially much more resilient that the original physical, single disk, version due to the virtue of the Target Platform. The Target Platform could be anything that the TurnKeyLinux Appliance can call home: a Scale Computing HC3 cluster, A Nimmbox cluster, or your traditional VmWare ESX cluster.
-  The TurnKey Linux VM can then either be replicated to a second cluster of your choice using internal features of that platform, or it can be conveniently backed up to the TurnKey HUB cloud backup service: tklbam. 

.. _TurnKey Core: http://www.turnkeylinux.org/core
