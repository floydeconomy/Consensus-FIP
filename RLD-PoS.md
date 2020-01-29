## Introduction to Reputed Liberal Radicalism Proof of Stake (RLD-PoS)

Participants in the consensus have a reputation, whereby, their reputation grows the longer they participate in consensus decisions. Each participant stakes a certain amount of coins into the system and this will allow them to start generating reputation in the system. The reputation in the system acts as a mechanism to allocate voting power to each participant.

Now let’s formally define voting power in the system.

> Voting Power of A Participant = Participant Reputation / Total Reputation in the system

### Block Reward Mechanism

Block rewards that are generated are placed in a self-governed account that issues out the rewards in cycles (a cycle refers to an arbitrary period of time).

At each cycle, each participant in the consensus will be allocated a certain amount of voting power based on their reputation. They are then allowed to use this voting power to delegate votes based on concepts related to Quadratic Voting. This ensures that the n'th vote has a cost of `n`. This means that even with a strong reputation, participants still have to pay a significant amount of votes to influence block reward allocation.
Then, at the end of the cycle, the block rewards and fees are rewarded to the participants based on the votes allocated to each participant.

This would allow us to leverage the benefits provided by quadratic voting and reputation by ensuring that new users must gain reputation before being able to vote in consensus decisions.

### Additional Scheme

Well, it's also possible to construct the same scheme without utilising reputation as a solution to gain voting power, also known as Liberal Radicalism Proof-Of-Stake (LD-PoS). However, LD-PoS is subjected to most of the issues related to Delegated Proof Of Stake (dPoS) which encourages plutocracy. But then, plutocracy can also occur in RLD-PoS, but the lower bound of plutocracy is much higher in RLD-PoS.

### Important Caveats

1. This is highly conceptual to encourage discussion from the community. It focuses on concepts related to Liberal Radicalism to figure out methods to construct consensus algorithms.
2. Proves for Proof-Of-Reputation ([Section 6.2](https://eprint.iacr.org/2018/239.pdf)), however, it's important to note that the paper discusses computational power based reputation instead of actual stake.

### Related Concepts:

1. [Quadratic Payments: A Primer](https://vitalik.ca/general/2019/12/07/quadratic.html) by Vitalik Buterin
2. [Developer incentivization: in-protocol contract author fee rebates](https://ethresear.ch/t/developer-incentivization-in-protocol-contract-author-fee-rebates/6179) by Vitalik Buterin
3. [RepuCoin: Your Reputation is Your Power](https://eprint.iacr.org/2018/239.pdf) by Jiangshan Yu, David Kozhaya, Jeremie Decouchant and Paulo Esteves-Verissimo
