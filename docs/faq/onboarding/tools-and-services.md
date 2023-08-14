---
sidebar_label: 'Tools and Services'
sidebar_position: 2
---

# Tools and Services

## I am a developer. Where do I start?

If you are a developer and want to use the LUKSO Blockchain, you can start by experimenting with the [Public Testnet](../../networks/testnet/parameters) and reading the [developer's guides](../../guides/universal-profile/create-profile). Please join our [Discord](https://discord.gg/lukso) and get in touch if you have ideas for the new digital lifestyle economy!

## Are there any sample projects to look at?

If you want to experiment with simple code snippets for LSPs, please look at the [LUKSO Playground](https://up-test-dapp.lukso.tech). The project can be used right in the browser or cloned locally. You can also play with our [Sample dApps](https://examples.lukso.tech), covering token and NFT creation, simple contract interactions, and a Forum prototype.

## Which tools can be used to develop dApps on LUKSO?

We have a [full set of tools](../../tools/getting-started/) and libraries that you can use to build on LSPs and interact with Universal Profiles. You can also [install the latest Universal Profile Extension](../../guides/browser-extension/install-browser-extension) to connect Universal Profiles with dApps.

## Where can I get LYXt for test deployments?

Our official [Testnet Faucet](https://faucet.testnet.lukso.network) is handing out LYXt to deploy smart contracts to the LUKSO Testnet. You will need a Twitter account to request funds.

## Is there a testing environment for the Universal Profile Extension?

If you want to experiment with the Universal Profile Extension and its interaction behavior, please look at our [Universal Profile Test dApp](https://up-test-dapp.lukso.tech).

## Can I check what LSP standards are used for specific contracts?

Yes. You can use the in-browser [inspection tool](https://erc725-inspect.lukso.tech/).

## What is a transaction relay service?

A transaction relay service, often referred to as a relayer, is a solution designed to **improve the blockchain user experience** by addressing the issue of gas fees - the costs users pay when executing transactions on a blockchain.

Typically, users must have the blockchain's native token to pay these gas fees. However, a relayer works around this problem. Users can **send their signed transactions** to the relayer. The relayer will then **execute the transaction on their behalf and cover the associated gas cost.**

Payment to the relayer can be handled in different ways. One option is an on-chain payment where the fees are deducted directly from an on-chain balance. Alternatively, users can set up an off-chain agreement with the relayer service via a subscription that gives them a monthly allowance for relayed transactions. This flexibility allows users to **choose the method that best suits their needs**.

## What is social recovery?

For conventional Ethereum accounts, also known as Externally Owned Accounts (EOAs), losing your private key can be disastrous as it's the sole means of accessing your account. If it's lost, access to the account and all its associated assets is also lost.

However, smart contract-based accounts like Universal Profiles offer more **flexible and secure solutions**. With Social Recovery, users can set up a recovery process that fits their needs. For instance, recovery could require permissions from pre-set trusted individuals (often called "guardians") or the provision of a secret phrase known only to the user, or even a combination of methods.

As Universal Profiles are natively able to support lots of EOAs as their controllers with different permissions, it's the perfect setup to build out social recovery schemes. The rotatable keys enable users to **regain access to their accounts securely**, even if they lose one private key, making the blockchain experience much more user-friendly and less risky.