Summary - The project calls for creating of multiple 'mirror' copies of crypto blockchains, placed on one or more cloud disk providers and making  a crypto daemon option to point to a cloud disk and not to a local disk


1.Intro

By design every user of private wallet of crypto-currency has to download the whole blockchain and store it on local disk or download the whole blockchain and store only the header (ETH-'fast'/BTC-'pruned' option).

In essence, everybody distrusts everybody and wants to download, verify and have a copy of the blockchain for themselves.

Even with the 'fast'/'pruned' option the amount stored on the local disk is 10s of GBs. The complete blockchain size is more than 1TB/ETH, 250GB/BTC and growing.

The situation places heavy burden on and discourages crypto-currency users who want to have their own local private wallets and/or to run a node. 

In order to have a private wallet users go to commercial wallet providers who have a single copy of the blockchain serving all of their users.  

The proposal calls for modifying of the main daemon of a crypto-currency to allow storing on a cloud drive.

This will create a limited number of trusted identical copies of the blockchain on cloud disks and save the crypto users from downloading and storing the whole or part of the chain.

The daemon will still have the original options of storing the blockchain to a local disk.



2. Benefits, pro-con

con - centralizing of the blockchain – limit the number of copies of the blockchain; place trust in a small number of blockchain copies;

pro – de-centralizing of wallets; moving away from commercial wallets; mass adoption of light private wallets from ordinary users; 

pro – every wallet can be a temporary node; 

pro – growth of permanent nodes; without the need to store large amount of data an user can consider running a light node on an arm system (raspberry pi) using home internet connection.

pro – spare the users of constant downloading and storing of the blockchain; slow down global warming, use less electricity and storage

pro - allow potentially quick redesign, adding features and update of the whole blockchain; 



3. Big picture

The initial step is implementing of cloud access to blockchain on ETH - having the largest blockchain. The next step is to propose and implement cloud access to ERC20 (and later) compatible blockchains, who are not on the Etereum chain and have their own wallets and blockchains. 

After this will come the implementation on BTC and other de-centalized blockchains.

The 'big picture' is creating of a light unified wallet for multiple cryptocurrencies. 

Potentially, this is a very large project. We are calling for contributors - developers, administrators, advisors, sponsors.

(Paul Arssov - project founder, arstech.biz)
