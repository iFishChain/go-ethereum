# iFish Chain

<div align="center">
  <img src="https://ifish.im/design/LOGO.png" alt="Logo" />
  <p>The iFish Chain protocol implementation.</p>
</div>

<div align="center" class="topLinks">
<strong>
<a href="https://coin.ifish.im/en/index.html" target="_blank" rel="nofollow">Web Site</a> | 
<a href="https://www.k5.ai" target="_blank" rel="nofollow">Wallet</a> | 
<a href="https://coin.ifish.im/en_whitepaper.pdf" target="_blank" rel="nofollow">White Paper</a> | 
<a href="https://github.com/iFishChain/ifish-chain" target="_blank" rel="nofollow">GitHub</a> | 
<a href="https://t.me/ifishyunyu" target="_blank" rel="nofollow">Telegram</a>
</strong>
</div>

## What is iFish Chain?

iFish Chain is a decentralized smart contracts  platform. Which is designed for new era universal crypto currency for games. Dedicated to over-centralized control of game assets, trade barriers between game platforms, exchange of game assets and other assets.

When a decentralized network is established, player's digital assets are fully written into the blockchain and given "absolute ownership." In addition, all gaming platforms can use the general digital currencies to trade, blockchain will ensure the authenticity and fairness of its currency.

## Building the source

For prerequisites and detailed build instructions please read the
[Installation Instructions](https://github.com/ethereum/go-ethereum/wiki/Building-Ethereum)
on the wiki.

Building geth requires both a Go (version 1.7 or later) and a C compiler.
You can install them using your favourite package manager.
Once the dependencies are installed, run

    make geth

or, to build the full suite of utilities:

    make all



## Running
By far the most common scenario is people wanting to simply interact with the iFish network: create accounts; transfer funds; deploy and interact with contracts. For this particular use-case the user doesn't care about years-old historical data, so we can fast-sync quickly to the current state of the network. To do so:

```
$ geth console
```

## License
iFish Chain is licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html), also
included in our repository in the `COPYING.LESSER` file.


