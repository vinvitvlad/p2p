# Cardano Blockchain Platform

## Overview

Cardano is a blockchain cryptocurrency platform based on [Ouroboros](https://eprint.iacr.org/2016/889) PoS consensus protocol. Cryptocurrency generated by the platform is Ada, coin is Lovelace. There are two main wallets for Ada - [Daedalus](https://daedaluswallet.io/) and [Yoroi](https://yoroi-wallet.com/)

Cardano was launched in 2017 by Ethereum co-founder [Charles Hoskinson](https://en.wikipedia.org/wiki/Charles_Hoskinson) and his Hong-Kong based company [IOHK](https://iohk.io/). Project has a long term [roadmap](https://roadmap.cardano.org/en/) which is divided into 5 basic periods called “eras”

1. Byron. Initial development
2. Shelley. Decentralization
3. Goguen. Smart contracts
4. Basho. Scaling
5. Voltaire. Governance
 
**Ouroboros PoS protocol basics**

Nodes with a positive stake are called stakeholders, and only stakeholders may participate in running the protocol. The Ouroboros protocol divides the physical time into epochs (5 days approx.), and each epoch is divided into slots (5 secs). Each slot has one leader. The slot leader has a (sole) right to produce one (and only one) block during his slot. Slot leaders are elected from the group of all stakeholders by electors (stakeholders who have enough stake) through non-deterministic Coin Tossing algorithm. The more stake stakeholder has, the more chances one has to be elected as a slot leader. Any stakeholder can delegate its shares to stake pool operators or run its own private pool to earn rewards on validating blocks. Rewards of current epoch could be collected after subsequent 2 epoch (10 days)

Full documentation on protocol implementation is [here](https://docs.cardano.org/)
 
## Economics

Project has huge market potential

Market Cap is more than 2 billions USD for now (10th place worldwide among cryptocurrencies). Average coin price is 0.07 USD with a strong potential to grow after the release of mainnet. Liquidity of Ada is 2%, main exchanges are Hitbtc, Binance and Huobi (according to [Coin360](https://coin360.com/coin/cardano-ada))

If coin reaches 1.45 USD per coin in nearest 5 years current participants would get 17x grow of their initial USD investments (according to [Crypto Rating](https://www.crypto-rating.com/price-prediction/ada/))

Running a staking pool could generate up to 12% annual return as reward (according to [Cardano official site]( https://staking.cardano.org))

**Note:** Current reward is subject to change in future releases but it shows realistic picture of earnings stakeholders can make
 
## Current state

Currently Cardano is on the second stage of it’s roadmap called Shelley which means that process of decentralization had been started

System had been deployed in the so-called Incentivized Testnet (Byron-to-Shelley transition phase) which is used for testing basic decentralization mechanisms. The mainnet phase will follow straight after at Aug 2020 approx. (according to [Cardano official forum](https://forum.cardano.org/t/the-public-testnet-is-now-open-for-business/34059))

![Cardano Roadmap](https://aws1.discourse-cdn.com/business4/uploads/cardano/original/3X/a/1/a1d38df2db5e68e0195137416123095679db7739.jpeg)

Staking and delegating machanisms are available. Anyone with enough competence could run a stake pool to validate blocks and earn pool operator’s reward. All rewards will be available in the following mainnet phase. More details are [here](https://staking.cardano.org/)
 
## Business plan

**Target:** 20 000 USD monthly revenue

To earn 20 000 USD monthly on validation rewards with 50/50 share of result among pool holder and delegators (~6% annual return for each) we need to control 0.5% of whole stake pool which is about 50 millions Ada or 3.5 millions USD (according to [official calculator](https://staking.cardano.org/calculator/))

### NPV

Lets calculate Net Present Value of our project

Imagine we need 10 average GCP/AWS nodes to hold our stacking pool. Each standard node (4CPU, 16GB RAM) costs 100 USD. So the fix cost of maintenance of pool is 1000 USD per month 

Imagine we need 1 devops engineer and 1 product owner full time with salary of 3000 USD monthly on that project

Imagine we need 1 year to find desirable sum of investment (3.5 millions USD) and the cost of acquisition is 1000 USD per month in the 1st year and 200 USD in subsequent years to compensate 20% of churn

We could calculate 3-years NPV of project

    NPV3 = 20000*24 - 1000*12 - 200*24 - 3000*2*36 - 1000*36 = 211 200 USD
 
### Acquisition

To supply our stake with money we need to find investors who interested in new and perspective cryptocurrencies

The main point of interest for them is the fact that Ada has huge potential to grow in the nearest 3-5 years (17x probably). So they can not only noticeably multiply their initial investment, but also get initial amount of money every year as annual reward in 5-year perspective (6%\*17=102%)

To find target investors we could use these acquisition channels
* current investors (more than 1500 according to [landing page](https://p2p.org))
* public lists of cryptocurrency investors (subject to search)
* targeted and context advertising (Facebook Ads, AdWords) to attract new people with interest in cryptocurrencies
