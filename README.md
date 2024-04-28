# HitchhikerStaking

# IIP-virtualStaking

### Idena Improvement Proposal (IIP): Implementation of a Liquid Staking Identity for Unvalidated addresses 

**Owner:** ubiubi18  
**Type:** Standard  
**Status:** Draft  

#### Abstract
This IIP introduces the concept of a "Virtual Identity" within the Idena network to allow unvalidated addresses to delegate their IDNA tokens, enabling them to participate in staking and earn rewards at a reduced rate. This approach is intended to enhance network growth and help to easier increase market capitalization.

#### Introduction
The current framework of the Idena network restricts staking to validated identities only, which inhibits growth by limiting participation to a smaller group of users. This proposal advocates for the creation of a Virtual Identity system that enables unvalidated investors to stake indirectly. It goes back to the idea of "hitchhiker staking" beeing discussed in https://medium.com/idena/idena-chronicles-116-119-44572e34d461

#### Motivation
The initiative to develop Virtual Identities stems from several identified needs:
- **Accessibility for New Participants:** Reducing the risk and barrier to entry for newcomers by providing a safeguard through indirect staking participation.
-  **Idena is hard to be integrated with DeFi and Liquidity Mining**: Current limitations hinder the development of DeFi and liquidity mining within the Idena ecosystem.

#### Specification
The Virtual Identity would operate as follows:
- **Structure:** It acts as a pooled entity that represents the combined stakes of unvalidated investors.
- **Staking Threshold:** Minimum treshold of IDNA comparable to the treshold of IIP-11 required to participate.
- **Withdrawal Fees:** Implementing a 0.5% burn fee on withdrawals to mitigate potential exploitation of the system.
- **Reward Distribution:** 50% of rewards to stakeholders, 50% to zerowallet. The rewards are generated continously as virtual reward drawing rights with every block, but there is no real mining node involved, just a smart contract with wrapped idna. those wrapped idna can be withdrawn from the smart contract as real idna, but there is a withdrawing-fee, burning 0,5% of the withdrawn funds

#### Rationale
Introducing Virtual Identities addresses several strategic goals:
- **Inclusivity:** Broadening the base of participants supports network security and value.
- **Lower Entry Barriers:** Provides a more accessible pathway for network participation.
- **Enhanced Network Appeal:** Facilitates the growth of decentralized applications by integrating a broader range of stakeholders.

#### Implementation
- ? help required ?

#### Impact Analysis
- **Network Participation:** It is anticipated that this system will diversify the stakeholder community, enhancing network security and resilience that way.
- **Economic Influence:** By engaging a larger group of stakeholders, the overall demand and value stability of IDNA are expected to improve.
-**enabling more predictable integration with defi:**
- Allow service providers like liquid staking providers to integrate with idena

#### Risk
There is a risk that existing investors will delegate their cold wallet funds to this mechanism, while no new investors join in. That way the rewards for idena identities could shrink without a compensation of growing marketcap on the other hand. So the idea could have negative consequences worst case instead of setting new incentives.

