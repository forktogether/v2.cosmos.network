# Intro - Hub

## The First Hub

The first blockchain in the Cosmos network is the Cosmos hub. The Cosmos hub connects to zones via the novel IBC (inter-blockchain communication) protocol and keeps a record of the total number of tokens in each zone. Because all inter-zone transfers go through the Cosmos Hub, you can send tokens from one zone to another, quickly and securely, without the need for a liquid exchange or trusted third party between zones.

The Cosmos Hub can connect to many different kinds of zones - public or private - as long as each zone speaks IBC. Tendermint-based Zones are natively compatible with IBC, but any fast-finality consensus algorithm can be used as a replacement. Cosmos can thus support a wide variety of currencies and scripting languages like those found in Bitcoin, Ethereum, ZeroCash, CryptoNote, and more. ATOM is the native token of the Cosmos Hub. It is a license for holders to stake and participate in governance.

## Proof-of-Stake

Blockchain networks are secured by a set of validators, who are responsible for committing new blocks in the blockchain. In Proof-Of-Work systems such as Bitcoin, validators are called miners, and the probability of a given miner to produce the next block is proportional to its computing power. In contrast, the Cosmos Hub is a public Proof-of-Stake blockchain. Proof-of-Stake is a category of consensus algorithm that relies on validators' economic stake in the network.

## ATOM

In the case of the Cosmos Hub, the frequency at which a validator is selected to produce the next block is proportional to the number of ATOM locked up (i.e. bonded, or staked).

These ATOM can be locked up by validators themselves, or delegated to them by ATOM holders that do not want or cannot run validator operations, called delegators. The sum of a validator's self-bonded and delegated ATOM is called its stake. The ATOM is the only staking token of the Cosmos Hub. In return for locking up their ATOM, delegators earn block provisions (in ATOM), block rewards (in Photons) and transaction fees (in whitelisted fee tokens). When a bonded ATOM holder wants to retrieve its deposit, it must wait for a 3 week unbonding period.

## Photons

ATOM are designed to be bonded on the Hub. This means that they are not ideal to pay fees or to move on other Zones of the Cosmos Ecosystem. This is why [Photons](https://blog.cosmos.network/cosmos-fee-token-introducing-the-photon-8a62b2f51aa?gi=b4641ddb5415) will be introduced. Photon is a fee token with much greater liquidity and velocity than ATOM. It is the second whitelisted fee token on the Hub after ATOM and can move on all the Zones that are connected to the Hub.

## Hard spoon

A hard spoon occurs when a new cryptocurrency is minted by replicating the account balances of an existing cryptocurrency. In our case, we are [hard spooning Ethereum](https://blog.cosmos.network/introducing-the-hard-spoon-4a9288d3f0df) by taking the account balances of existing Ethereum holders and mirroring those values. This means that ETH holders will have their coins replicated in this EVM zone and will be redeemable as fee tokens--Photons--within [Ethermint](https://ethermint.zone).

After launch, ATOM holders will be able to vote on the hard spoon, specifically:

- Whether the hard spoon should happen or not
- When the snapshot will occur
- How Photons are distributed (what goes to Ethereum holders, what goes to ATOM holders and Photon inflation)

## Validators

Validators of the Cosmos Hub are responsible for creating new blocks of transactions that are added to the blockchain. Running a validator is non-trivial. It requires technical knowledge and hardware investment. Additionally, due to the way that Tendermint???the underlying consensus engine on which the Cosmos Hub is built???works, the number of validators must be limited. Initially, this limit is fixed to 100. This means that only the top 100 addresses with the most stake that declared their intention to become validator will be validators. As a result, most ATOM holders will not be validators. Instead, they will become delegators, thereby participating in deciding who among the validator candidates actually become validators.

If you are interested in becoming a validator: [learn more about validators](/validators).

## Delegators

People that cannot, or do not want to run validator operations, can still participate in the staking process as delegators. Indeed, validators are not chosen based on their own stake but based on their total stake, which is the sum of their own stake and of the stake that is delegated to them. If you are interested in staking your ATOM to a Validator to earn revenue, or just want to learn more about delegators, read the [Delegators FAQ](/resources/delegators).
