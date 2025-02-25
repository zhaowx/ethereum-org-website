---
title: Pooled staking
description: An overview of how to get started with pooled ETH staking
lang: en
template: staking
emoji: ":money_with_wings:"
sidebar: true
image: ../../../assets/staking/leslie-pool.png
alt: Leslie the rhino swimming in the pool.
sidebarDepth: 2
summaryPoints:
  - Stake and earn rewards with any amount of ETH by joining forces with others
  - Skip the hard part and entrust validator operation to a third-party
  - Hold liquidity tokens in your own wallet
---

## What are staking pools? {#what-are-staking-pools}

Staking pools are a collaborative approach to allow many with smaller amounts of ETH to obtain the 32 ETH required to activate a set of validator keys. Pooling functionality is not natively supported within the protocol, so solutions were built out separately to address this need.

Some pools operate using smart contracts, where funds can be deposited to a contract, which trustlessly manages and tracks your stake, and issues you a token that represents this value. Other pools may not involve smart contracts and are instead mediated off-chain.

## Why stake with a pool? {#why-stake-with-a-pool}

In addition to the benefits we outlined in our [intro to staking](/staking/), staking with a pool comes with a number of distinct benefits.

<CardGrid>
  <Card title="Low barrier to entry" emoji="🐟">
    Not a whale? No problem. Most staking pools let you stake virtually any amount of ETH by joining forces with other stakers, unlike staking solo which requires 32 ETH.
  </Card>
  <Card title="Stake today" emoji=":stopwatch:">
    Staking with a pool is as easy as a token swap. No need to worry about hardware setup and node maintenance. Pools allow you to deposit your ETH which enables node operators to run validators. Rewards are then distributed to contributors minus a fee for node operations.
  </Card>
  <Card title="Liquidity tokens" emoji=":droplet:">
    Many staking pools provide a token that represents a claim on your staked ETH and the rewards it generates. This allows you to make use of your staked ETH, e.g. as collateral in DeFi applications.
  </Card>
</CardGrid>

<StakingComparison page="pools" />

## What to consider {#what-to-consider}

Pooled or delegated staking is not natively supported by the Ethereum protocol, but given the demand for users to stake less than 32 ETH a growing number of solutions have been built out to serve this demand.

Each pool and the tools or smart contracts they use have been built out by different teams and each come with their own risks and benefits.

Attribute indicators are used below to signal notable strengths or weaknesses a listed staking pool may have. Use this section as a reference for how we define these attributes while you're choosing a pool to join.

<StakingConsiderations page="pools" />

## Explore staking pools {#explore-staking-pools}

There are a variety of options available to help you with your setup. Use the above indicators to help guide you through the tools below.

<InfoBanner emoji="⚠️" isWarning>
Please note the importance of choosing a service that takes <a href="/developers/docs/nodes-and-clients/client-diversity/">client diversity</a> seriously, as it improves the security of the network, and limits your risk. Services that have evidence of limiting majority client use are marked as <em style="text-transform: uppercase;">"diverse clients."</em>
</InfoBanner>

<StakingProductsCardGrid category="pools" />

Have a suggestion for a staking tool we missed? Check out our [product listing policy](/contributing/adding-staking-products/) to see if it would be a good fit, and to submit it for review.

## FAQ {#faq}

<ExpandableCard title="How do I earn rewards?">
Typically ERC-20 liquidity tokens are issued to stakers that represents the value of their staked ETH plus rewards. Keep in mine that different pools will distribute staking rewards to their users via slightly different methods, but this is the common theme.
</ExpandableCard>

<ExpandableCard title="When can I withdraw my stake?">
Currently, withdrawing funds from a validator on the Beacon Chain is not possible, which currently limits the ability to actually <em>redeem</em> your liquidity token for the ETH rewards locked in the consensus layer.

Alternatively, pools that utilize an ERC-20 liquidity token allow users to trade this token in the open market, effectively allowing you to "withdraw" without actually removing ETH from the Beacon Chain.
</ExpandableCard>

<ExpandableCard title="Do pooled stakers need to do anything for The Merge?">
Pooled stakers <strong>do not need to do anything to prepare for The Merge</strong>.

However, as The Merge approaches, be on high alert for scammers. **You do not need to upgrade your ETH or staked ETH tokens** for the transition to proof-of-stake.

Learn more about [The Merge](/upgrades/merge/)
</ExpandableCard>

<ExpandableCard title="Is this different from staking with my exchange?">
There are many similarities between these pooled staking options and centralized exchanges, such as the ability to stake small amounts of ETH and have them bundled together to activate validators.

Unlike centralized exchanges, many other pooled staking options utilize smart contracts and/or liquidity tokens, which are usually ERC-20 tokens that can be held in your own wallet, and bought or sold just like any other token. This offers a layer of sovereignty and security by giving you control over your tokens, but still does not give you direct control over the validator client attesting on your behalf in the background.

Some pooling options are more decentralized than others when it comes to the nodes that back them. To promote the health and decentralization of the network, stakers are always encourage to select a pooling service that enables a permissionless decentralized set of node operators.
</ExpandableCard>

## Further reading {#further-reading}

- [Staking with Rocket Pool - Staking Overview](https://docs.rocketpool.net/guides/staking/overview.html) - _RocketPool docs_
- [Staking Ethereum With Lido](https://help.lido.fi/en/collections/2947324-staking-ethereum-with-lido) - _Lido help docs_
