# Segment_Routing

# **Description**

The master’s thesis mainly focuses on analyzing the "Network programming" capabilities
of Segment Routing over IPv6 (SRv6) and its performance and architectural design. In
traditional IP forwarding, routers follow the control-plane instructions such as ISIS and
BGP to transfer the packets to the destination address. This helps routers to choose shortest
paths and forward is performed hop-by-hop using destination-based longest prefix matching,
with routing agility distributed across all nodes. But SRv6 offers source-driven forwarding
algorithms in which an ordered set of instructions, described as Segment Identifiers (SIDs), is
encoded directly within the IPv6 packet extension header. It uses packet carry instructions,
so routers no longer compute per-flow path decisions but execute instructions encoded in the
packet. Routers just execute the instructions without computing the per-flow path decisions.
The micro-SID mechanism introduces a compressed encoding architecture that enables
multiple SIDs to be embedded within a single IPv6 packet . The network system
moves to a distributed instruction execution system from a simple forwarding fabric system.
This method is considered a form of "Network Programming". The primary objective of this
thesis is to observe the SRv6 mechanisms in a simulated model and analyze their behavior
forwarding efficiency, scalability, and path determinism. This knowledge can be used in the
THM laboratory for future teaching or research purposes or laboratory development.



