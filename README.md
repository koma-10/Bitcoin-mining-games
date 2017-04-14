# Bitcoin-mining-games
A concept paper on Bitcoin mining games
INTRODUCTION

Bitcoin is a network protocol that enables individuals to transfer property rights on account
units called "bitcoins", created in limited quantity. When an individual sends some bitcoins to
another individual, this information is broadcast to the peer-to-peer Bitcoin network. However,
for technical purposes we won’t address here, this transaction needs to be included – together
with other transactions forming a block – in the blockchain in order to be confirmed and secured.
As a consequence, the blockchain is a public ledger that contains the whole history of all
the transactions of bitcoins ever processed and all Bitcoin users can trust this decentralized,
distributed ledger.

It is the role of miners to do this work of confirming and securing transactions through
insertion in the blockchain. Practically and slightly simplifying, for any miner, this work consists
in considering a set of transactions that are present in the network, solving a mathematical
problem that depends on this set and spreading the result to the Bitcoin network for this solution
to be checked and for it to reach consensus. Once all these steps are done successfully, the set of
transactions considered by the miner forms a block that is added on top of the blockchain. The
first miner to succeed in this process is rewarded in bitcoins for his useful work.

In the current implementation of Bitcoin, this reward comes from both an ex-nihilo creation of
some new bitcoins and some fees Bitcoin users can add to their transactions. Since some bitcoins
are created in the mining process and in order to control the monetary base, mining is made more
complex than it could be. And, since in a first approximation, the probability for each miner to
solve a mining problem depends on his computational power, the complexity of mining is made
proportional to the total computational power of all miners. More precisely, the complexity is dynamically adjusted so that a block solving – and hence a creation of bitcoins – occurs every
ten minutes in expectation. Once a block is inserted in the blockchain, the mathematical problem
faced by all miners are modified and we can consider that a fresh new speed game starts between
miners. Hence, the whole building of the blockchain can be considered as independent block
insertions from the miners’ point of view.
