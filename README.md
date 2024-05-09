# reputation_based_blockchain Simulation

A reputation-based mechanism that allows each node to compute a
reputation value for each of its neighbors. Intuitively, a node
forwarding more valid and fewer spam transactions would have a
higher reputation.

 A verification strategy that allows the system to reduce the spread of
 spam transactions by selectively verifying a proportion of the received
 transactions. A node will be more likely to verify a transaction from a
 disreputable sender

 
paper
 https://ieeexplore.ieee.org/document/9625746
<pre>
 Motivation
 • To increase the throughput of non-spam transactions.
 • To avoid the increase of transaction fees of non-spam transactions.
 • To reduce the uses of computational resources for verifying spam 
transactions
</pre>
 ![image](https://github.com/sannu01/reputation_based_blockchain/assets/53299324/22768351-c331-4356-a741-c090009072ae)

Simulation Environment
<pre>
 • Testing done for 100 time slots for 3 different Environments.
 • 80% Honest Node and 20% Malicious Node
 • 70% Honest Node and 30% Malicious Node
 • 60% Honest Node and 40% Malicious Node
 • Only Honest Nodes validate the transaction with probability function.
 • Reputation Attenuation after every 10 time slots.
 • Test done on 2000 Nodes with each Node having 2% probability of 
generating new transaction in each time slot
</pre>


Simulation Result



<pre>As the number of Malicious node increases in the network the number of invalid transaction 
 spread decreases compared to when Malicious Nodes were lessbecause the proportion of valid 
 transation decreases and the reputation valus of node does not increases to let them attack the network.</pre>
![download](https://github.com/sannu01/reputation_based_blockchain/assets/53299324/ecac3d1b-1f94-484d-8671-da0ec9c21e21)
