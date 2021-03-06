## Dr. TLA+ Series - Fast Paxos (Cheng Huang)

### Time
August 29, 2016 - 10-11:30am PDT

### Abstract
Replicating data across geographically distributed data centers is the new norm in cloud services. Compared to Classic Paxos, Fast Paxos shines more favorably, because
+ replication can be initiated from arbitrary DC (and there is no need to pump data through a dedicated primary DC);
+ replication can be completed in single WAN round trip.

This meetup studies Leslie Lamport's seminal paper on Fast Paxos and its TLA+ specification.

### Bio
[Dr. Cheng Huang](http://research.microsoft.com/~chengh) is a research scientist and tech lead at Microsoft. Cheng has been with Microsoft Research for 11 years. Most recently, he joined the Azure Storage team to full-time help making the Microsoft cloud more scalable and cost effective.
 
### Prerequisite
+ none
+ most helpful to review [Andrew Helwer's lecture on Classic Paxos](../Paxos/README.md)

### Paper and Spec
(not required, but helpful to take a quick look)
+ [Fast Paxos](https://www.microsoft.com/en-us/research/publication/fast-paxos/)
+ [TLA+ specification](./FastPaxos.tla)

### Media
+ [video](https://www.youtube.com/watch?v=eW6Zv0X53T4)
+ [slides](./FastPaxos.pdf)

[back to schedule](https://github.com/tlaplus/DrTLAPlus)
