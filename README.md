# trusty

Collateral is the core security mechanism for DeFi protocols. Dai, Compound, Synthetix and others rely on agents to lock their coins, which in turn back newly created assets.
Locking collateral, however, represents an opportunity cost for agents: they could use these coins to e.g. become a staking node in Ethereum or trade their coins for a profit on exchanges. 
We propose trusty, a system that allows agents to lower their collateral in a wide range of protocols implemented on Ethereum. 
Notably, the decrease of collateral provides the same level of protection against economically rational adversaries as before. 
To achieve this security property, the decrease of collateral has a lower boundary at the expected opportunity cost of having the collateral locked in a given protocol. 
Further, agents need to continuously perform "desired actions" in a protocol to enjoy the lower collateral bounds.


## Protocol idea

The basic protocol idea is documented in this [overview](docs/trusty.md).

## Implementation

Work-in-progress.
