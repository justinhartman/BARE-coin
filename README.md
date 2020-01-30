### Developement Version! Don't Use! 
-------------------------------------------------------------------------------------------------------------------------------
*** BETA SOFTWARE - USE AT YOUR OWN RISK ***

BARE 2.0
BARE Coin integration/staging repository
=====================================

BARE is a cutting edge cryptocurrency, with many features not available in most other cryptocurrencies.
- 100% Proof of Stake 3.0 Consensus protocol, allowing very low transaction fees and energy expenditure, and staking rewards to all participants in the network
- Masternode technology used to secure the network and provide the above features, each Masternode is secured
  with collateral of 1K BARE
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

385000 BARE was produced for swapping.

## Coin Specs ##
<table>
<tr><td>Hash Type</td><td>SHA256</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every 10 blocks</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>~1,4 million</td></tr>
</table>

## PoS Rewards Breakdown ##

<table>
<th>Block Height</th><th>Reward</th><th>Masternodes</th><th>Stakers</th><th>Budget</th>

</table>

## BARE resources ##
* Client & Source:
[Client Binaries](https://github.com/BareCrypto/BARE-coin/releases)
[Source Code](https://github.com/BareCrypto/BARE-coin)
* Links:
[Homepage](https://bare.network)
[Explorer](https://explorer.bare.network)
[Exchange Crex24](https://crex24.com/exchange/BARE-BTC)

[Discord](https://discord.gg/HqHutDk)
[Twitter](https://twitter.com/bare_crypto)
[BitcoinTalk](https://bitcointalk.org/index.php?topic=5149503)

## Nodes & ports ##
dns1.bare.network<br>
dns2.bare.network<br>
dns3.bare.network<br>
dns4.bare.network<br>
p2p port :

## Importing wallet balances from BARE 1.1.1.0 wallets into BARE 2.0 wallets ##

BARE has migrated to a completely new codebase, and as such, is no longer compatible with the previous network and blockchain used by the old 1.1.1.0 wallets.
As part of the migration to the BARE 2.0 wallets and network, users can redeem their old wallet balances* into their new wallets.
This process is simple, but if not done correctly could risk you losing all your coins.

## NEVER UNDER ANY CIRCUMSTANCES GIVE AWAY YOUR PRIVATE KEYS TO ANYONE, THE ONE WHO HAS YOUR KEYS CONTROLS YOUR BARE ##

Please follow these simple steps
1) BACKUP your old BARE wallet, make multiple copies (most critical is your wallet.dat file!)
2) Copy that back up somewhere safe e.g USB drive, seperate computer.
3) Make a list of your wallet addresses (you may need to look in "coin control" for a full list). If coin control is not available in the send tab of your wallet, then activate this under `Settings / Options / Wallet / Enable Coin Control Features`
4) For each wallet address (that you know has a balance of BARE) in debug console run `dumpprivkey enteryourbarewalletaddresshere`
5) Record the private key (securely & safely) that is printed there
6) As per item 2) Backup your old BARE wallet (just to be sure).  Again, critical is your wallet.dat file
7) Uninstall your old BARE wallet IF you are installing the 2.0 wallet on the same machine (to avoid any conflicts). For the sake of safety, you may also rename your BARE folder to say BARE-1.1.1.0-backup so it is preserved on your machine if things go wrong.
8) Install the new BARE 2.0 wallet
9) In debug console run `importprivkey EnterYourPrivateKeyHere "comment"`

You should now see your old BARE balance re-instated into the new BARE 2.0 wallet.
For security, we *strongly recommend* you now send those coins to yourself to a newly generated receive address created in your own 2.0 wallet.

For support, please don't hesitate to join us in our chat platform at http://discord.gg/HqHutDk

*Only transactions up to and including block 400000 will be processed
