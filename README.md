# Web3 By Example
Node.js with Web3 javascript example scripts for getting basic information (transactions, balances, ether, and tokens) from the Ethereum blockchain.

## What Is?
I'm not a developer. However I really wanted to get into how to write code that interacts with the Ethereum blockchain, being one of the more interesting blockchain projects I figured it would be a good place to learn how to use the infamous "blockchain" in a website or just in the console using some javascript.

This proved to be quite the challenge, as previously stated I'm not a developer. Googling found some good examples, but a lot of what I ended up with was more or less code I wrote. Now that being said, any professional ~~might~~ will notice my code isn't perfect. Originally I was going to make a Medium article with all this, but having someone help or rather fix errors would be WAY easier on Github... so here we are.

## Set Up
I used a Ubuntu server to test these, you will need either a similiar setup or you can use your own machine. I don't want (nor am I able to) describe how to get your system ready only that you will need to install the following:

- Node.js (8.7.0)
- Web3 Module (1.0.0)
- *OPTIONAL* Geth (1.7.1 or the latest version)

You can use npm to install Node and Web3. Geth will require a little extra TLC, so I suggest you instead get an [Infura API](https://infura.io/) token to use, its free and you'll get full access to the Ethereum blockchain without actually running your own node.

It is also a fantastic idea to have the Web3 documentation open so you can get more information on functions and other things that may be useful; you can find that here: http://web3js.readthedocs.io/en/1.0/getting-started.

## Running Scripts
I'm going to assume you know at least the basics of what Ethereum is and what terms like Address, transaction hash/ID, and tokens means. If not, you may want to read up on that before anything else. I've left placeholder text in place of where you will need real Ethereum value; you can either use your own or just grab a random one from a block explorer like [etherscan.io](http://etherscan.io/).

To execute you simply use the console in run ```node example-script.js``` and the results will be printed in the console.

In addition each script has a markdown file with the same name. In there you'll find an explanation of whats happening, this was done for the really noobish among us (myself included) can see what exactly is happening.

## Additional Notes
Web3 1.0.0 is at the time of this edit, beta. I actually have no idea why when I installed it it chose to use the beta version, probably an error on my part. That being said, it does work so while it may not be ideal for production it should suit the needs of someone who just wants to learn and run a few scripts. 

I really did want to make a website with these and have the results show up on the page, but the effort was too much for me plus my javascript ability was not up the task. 

Again, not a developer. If there is something wrong with what I wrote here or with a script, please call me out on it or request to change it. I hope this is able to help other newbies learn more about Ethereum and the only way that's going to happen is with help from more competent developers.

Ĝis Poste, TXTCLASS.
