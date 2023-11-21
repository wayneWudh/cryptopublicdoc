URL: https://pyth.network/blog/what-is-the-pyth-network
Everything You Need to Know About the Pyth Network | Pyth NetworkProducts Price FeedsReal-time prices for smart contractsBenchmarksHistorical Pyth market dataEcosystem Explore the EcosystemMeet Pyth UsersCommunity HubSee Data ProvidersBecome a Data ProviderPyth StatsDune DashboardDevelopers DocumentationStart integrating Pyth data feedsGet StartedHow Pyth Works On-Demand Updates Pythnet Price Feeds TradingView Integration TutorialsIntegrate on EVM (On-Demand) Integrate on EVM (Pusher) Integrate on Solana Integrate on Other Chains Price Feed IDsGitHubResources Get in TouchResourcesPodcastsVideosNewsUse CasesCareersData Driven 2023Blog Products Price FeedsReal-time prices for smart contractsBenchmarksHistorical Pyth market dataEcosystem Explore the EcosystemMeet Pyth UsersCommunity HubSee Data ProvidersBecome a Data ProviderPyth StatsDune DashboardDevelopers DocumentationStart integrating Pyth data feedsGet StartedHow Pyth Works  On-Demand UpdatesPythnet Price FeedsTradingView IntegrationTutorialsIntegrate on EVM (On-Demand)Integrate on EVM (Pusher)Integrate on SolanaIntegrate on Other ChainsPrice Feed IDsGitHubResources Get in TouchResourcesPodcastsVideosNewsUse CasesCareersData Driven 2023Blog Privacy PolicyTerms of Use back03 Nov 202313 min readEverything You Need to Know About the Pyth NetworkShare:Decentralized finance (DeFi) promises to revolutionize the way we manage our money and empower individuals to take control of their financial lives. The vast majority of DeFi services require a blockchain oracle—a secure, reliable method for blockchain applications to obtain financial data from the external world.Enter the Pyth Network, the largest first-party oracle network for publishing financial market data on-chain. The network sources its data from over 90 first-party data providers, including some of the biggest exchanges and market makers. Pyth offers real-time price feeds for cryptocurrencies, equities, foreign exchange pairs, ETFs, and commodities to smart contract developers on more than 40 blockchains.Since April 2021, the contributors of the Pyth Network have been working to provide Web3 developers with hundreds of real-time price feeds. The mission is to make all of the world's financial market data available on the blockchain for developers everywhere.With the blockchain industry moving towards a future of high throughput DeFi, there is a rapidly growing demand for low-latency, high-frequency on-chain data. This blog post delves into the Pyth Network’s role in enabling this transformation.Why Do We Need Another Oracle?The Pyth Network is not the first blockchain oracle. The contributors behind Pyth began this project in DeFi Summer of 2020 because they noticed a gap in blockchain infrastructure that held back the promises of the blockchain space. Simply put, a price oracle for ultra-low-latency, institutional-quality market data did not exist. Web3 developers felt this gap in three ways:1. Speed: Oracles were not updating fast enough for many financial use cases.If prices on the blockchain are slower than real-world markets, then DeFi services will be inaccurate and even vulnerable to malicious attacks. These restrictions prevent developers from building sophisticated financial services. At the time, price oracles only updated every 10-60 minutes or ‘heartbeat’, which cannot support use cases that require low-latencies and high-frequency updates.2. Coverage and Availability: Developers did not have access to the price feeds they needed.Developers need access to certain assets or markets to serve their users. Developers cannot deliver financial services if the relevant price feeds are not available on their blockchain of choice. Legacy oracles could have e.g. 200 price feeds on Ethereum but only 8 on a newer chain like Base. The same oracle could also support multiple chains but have only a few price feeds that are available on all supported chain. These limitations can delay a protocol’s roadmap.3. Sourcing and Quality: Data was opaque and came from aggregated, third-party sources.Price oracles can be responsible for securing billions of dollars of smart contract value. But if the ultimate source of their data is opaque, developers and users cannot trust the quality of the prices they receive. Additionally, it will be difficult to hold these sources accountable for their prices, especially if the oracle is collecting these prices from public aggregator services or scraping services. Developers must be able to verify the inputs from their oracle's data sources and understand the reputations at stake.How Pyth WorksThe Legacy Model for Data DistributionThe Pyth Network is designed to solve these three limitations. These shortcomings arose because traditional oracles were designed based on a fundamental misunderstanding of how financial data works.The implicit premise behind many legacy oracles is that all data, including financial data, is freely available in the Web2 space. According to this approach, the oracle provider simply needs to incentivize network participants to fetch this data, come to a consensus, and bring it on-chain.A network of nodes will collect or scrape data from public resources, including aggregators compiling third-party data from other undisclosed sources. This method of data sourcing may work for public datasets such as weather or sports data. However, when it comes to financial data, the oracle must make compromises in terms of data quality, costs, and scaling. Furthermore, some financial data cannot be redistributed freely due to IP laws.Consider the financial exchange industry. In 2022, the largest traditional exchanges earned $6.6B in total for data fees alone. Subscriptions to professional data terminals like Bloomberg costs tens of thousands of dollars per year. Even crypto exchanges like Coinbase have started charging for market data. The financial data industry operates as a walled garden.The alternative solution—non-paywalled data—is either delayed for free users or aggregated by freemium services not tailored for smart contracts. Legacy oracles cannot access the first type of valuable data without violating IP laws. Smart contract developers therefore get the second-best data, at the expense of DeFi users.A New Model for Data DistributionThe Pyth Network is built on the understanding that financial data is valuable and not freely attainable. Instead of serving a rough approximation of this data, the Pyth protocol empowers and incentivizes original owners of financial data to contribute it directly to the blockchain. The network’s data sources are called “first-party” because they create and own the data that they contribute.It is helpful to visualize Pyth as a decentralized marketplace for market data. On the one side, creators of proprietary data represent the suppliers. Applications using this data represent the consumers. In the same way that Airbnb brought more vacation homes and spare rooms to the travel industry, Pyth Network unlocks more high-quality data for the blockchain industry by incentivizing data owners to contribute.The Future of DeFi is First-PartyOne might ask why Pyth Network’s architecture will remain the industry’s new go-to financial oracle. The answer lies in the long-term implications of first-party price data.Pyth Network’s first-party data model future-proofs it for DeFi’s expansion into new asset classes such as energy, treasury rates, and real-world assets which do not have free-to-access equivalents online. The distribution rights that come with Pyth's first-party data provider community ensure that the network is prepared for DeFi's expansion. If DeFi grows to serve millions or even billions of users, we should expect that it will offer new markets. Oracles need to be where DeFi grows.A helpful illustration of these different architectures is to think of music streaming services. Reporter oracle networks are analogous to Napster, where CD purchases act as network nodes who purchase instances of the original music and distribute it to the Internet of listeners.Napster faced severe legal consequences and spam attacks because of this model. Spotify provided a streamlined solution where musicians and record labels can directly stream to subscribers and earn from the platform’s economics. Pyth is analogous to Spotify in its acknowledgment and rewarding of owners of intellectual property—in this case, financial data.Pyth Network is the largest publisher oracle network with over 90 first-party data sources publishing directly to the network. In this network, the nodes own and publish their data directly on-chain.Because Pyth’s data providers are the owners of the data they contribute, the financial data can be freely distributed across the blockchain space and beyond. This data distribution model also maximizes access to information and removes middlemen costs for data consumers. The design brings speed and cost advantages which enables Pyth to scale to thousands of symbols and near limitless blockchains in coverage.In contrast, most legacy oracles are reporter oracle network, where nodes carry data over the last mile from API endpoint to on-chain consumption. In this network design, the nodes must purchase the data from first-party sources or other middlemen for transmission. These networks are constrained by the cost, speeds, and output formats of the purchased data. You can learn more about the sustainability differences between publisher and reporter oracle networks here.Although there is no single right way to design an oracle network, the Pyth Network is designed to scale without speed, pricing, or distribution constraints. The goal is to enable the next generation of Web3 capital markets.The next section breaks down the Pyth Network to its core components to help illustrate how its core products work.The Pyth Network ComponentsThe Pyth Network allows market participants to publish pricing information on-chain for applications to use. The protocol is an interaction between:Data providers submit pricing information to Pyth's oracle program. Pyth has multiple data publishers for every product to improve the accuracy and robustness of the system.The Pyth protocol combines providers' data to produce a single aggregate price and confidence interval.Data users read the price information produced by the oracle program.It is important to understand that the Pyth Network itself is not a source of data. Data providers supply data to the network, and data users demand this data. The Pyth protocol, as a decentralized marketplace, aggregates the data providers’ contributed data in preparation for delivery to applications across multiple blockchains.Data ProvidersThe Pyth Network data provider community is comprised of global exchanges, trading firms, market makers, and other institutional as well as decentralized market participants. These providers are the creators, and therefore owners, of their price data. The data providers contribute their idea of the price of assets e.g. Bitcoin to the network for the Pyth Price Feeds.Though it may seem counter-intuitive, there is no single true price of an asset. There is the price you can trade an asset at, which is generated by exchanges; and there is the most recent transaction price of that asset, which is generated by traders. Pyth’s data provider community specializes in these two types of price data.The Pyth ProtocolThe Pyth protocol aggregates the data providers' inputs to produce a single aggregate price and confidence interval every 400ms for each price feed. This aggregation mechanism lives on an application-specific blockchain called Pythnet.Consider the symbol BTC/USD. Each provider reports both their price and a confidence interval estimate for Bitcoin to the BTC/USD price feed on Pyth. For example, a provider may provide a price of $30,000 ± $5. Multiple providers contribute their inputs for any price feed, resulting in a robust, accurate output.Pythnet is configured to be a proof-of-authority chain. It runs a version of the Solana validator and is a completely separate network from Solana mainnet-beta. The Pythnet appchain processes data from various providers, combining their inputs to produce a unified price and confidence interval for each price feed.The aggregation algorithm is designed to make each price feed robust to outliers and manipulation, weigh each data source appropriately based on their accuracy, and reflect variations between data providers’ prices an aggregate confidence band. The aggregate outputs are then streamed to Wormhole in preparation for dApps to use: the result is a signed price payload that can be verified on any chain where Pyth is supported. You can read more about the aggregation methodology here.Data UsersData users on any Pyth-supported blockchain can read the price feeds and incorporate the data into their smart contract logic.Pyth Network introduces a unique architecture called the Pull Oracle. With the Pull Oracle design, data users can “pull” or request a price update from the Pyth protocol when needed. This architecture is gas efficient because users only pay for prices they want.Thanks to this design, decentralized applications can request a new price update from the Pyth protocol when needed. A user would submit the signed price payload to the Pyth contract on their blockchain, which verifies its validity, and then use the resulting price. This process allows Pyth price updates to reach any supported blockchain.In contrast, legacy oracles are typically designed as Push Oracles. These oracles run an off-chain process to “push” price updates on-chain at a regular interval. This model can waste gas fees on unused price updates. The inefficiency of push oracles can lead to gas subsidy requirements, infrequent updates, and difficulties landing prices on-chain during network congestion.The Pyth protocol allows data users to request and consume on-chain price updates for a small data fee. Pyth users pull sends tens of millions of price updates cross-chain every month onto the various supported blockchains. While data fees are currently set to the smallest denomination of the blockchain’s native currency (e.g. 1 wei), this fee parameter and others can be determined by future governance.Common use cases of Pyth data include spot and derivatives exchanges, structured product vaults, borrow/lending platforms, stablecoin protocols, yield optimizers, asset management solutions, and data analytics. You have probably used a Powered by Pyth application. Notable names include Synthetix (Optimism), Vela Exchange (Arbitrum and Base), Alpaca Finance (BNB Chain), Solend (Solana), and many more.The Pyth Network ProductsThe Pyth Network currently offers two flagship products for DeFi applications: Pyth Price Feeds and Pyth Benchmarks.Integration with Pyth data is permissionless, meaning developers can access Pyth data without entering a subscription or engaging a sales team. This design choice reflects the network’s commitment to the Web3 ethos.Pyth Price FeedsThe Pyth Network offers over 350 low-latency price feeds across cryptocurrencies, FX rates, equities, ETFs, and commodities. Each price feed updates once every 400ms: high-frequency updates mean the prices closely track the external markets to granular intervals. High resolution data is important for time- and price-sensitive applications.Every Pyth Price Feed provides the spot price and a confidence interval, visualized as a band around the price. The confidence interval represents the range in which the data providers (in aggregate) believe the true price is likely to be. This confidence value informs data users about the strength of the price output. Data providers can adjust their confidence based on the liquidity environment, and smart contracts can use this information for safer operations.Pyth BenchmarksPyth Benchmarks allow users to query a historical archive of prices from the Pyth Price Feeds. Benchmarks are class of standards used in finance to guide decisions and settle payouts. Examples include reference prices like the Bitcoin reference rate, indices like the S&P500, and rates such as LIBOR or the Fed Funds Rate.Pyth Benchmarks provide standardization in calculations and presentation, ensuring consistent measurements for settlement and valuation. Common use cases for Pyth Benchmarks include decentralized options vaults (DOVs), such as Aevo on Ethereum, and backfilling prices for perpetual trading settlement, such as Synthetix on Optimism.Addressing the Limitations of Legacy OraclesHow do Pyth Network’s products address the issues of speed, asset coverage, and accuracy of legacy oracles? The key is Pyth Network’s architectural innovation of the Pull Oracle. This efficiency brings a number of advantages in latency, scalability, and data resolution.1. Low-Latency, High-Frequency UpdatesHigh Update Frequencies—The Pythnet appchain updates each Pyth Price Feed multiple times per second. The output is streamed to Wormhole and data users can listen to this data stream through a public API. Pushing every price on-chain would make frequent updates like this impractical. However, push oracles usually update even less frequently than the blocktime due to the high cost of more frequent updates.Low-Latencies—Pythnet streams price updates at a high frequency off-chain so that decentralized applications can use the most recent off-chain price for every transaction. This outcome means fresher prices than relying on a last on-chain update pushed by an oracle.2. Price Feed Coverage and Multi-Chain AvailabilityBroad Asset Selection—The technical capabilities of Pythnet enables the Pyth protocol to scale to thousands of price feeds. This is thanks to Solana’s specialization in high-throughput and ultra-cheap transactions.Multi-Chain Availability—The Pyth Network's price feeds are accessible on all Pyth-supported blockchains by default, since price sourcing and aggregation occur on Pythnet, and the price updates are brought cross-chain through Wormhole. When a new Pyth Price Feed launches, it is immediately available on all supported blockchains, eliminating the need for individual deployments on each target chain. This makes Pyth an interesting oracle for launching new data feeds, as Pyth can instantly expand price exposure for an asset to dozens of blockchains.3. High-Resolution, High-Fidelity, Transparent DataAccurate, First-Party Prices—Pyth sources data from traditional and decentralized creators of financial data. One key advantage of Pyth’s focus on first-party data is price accuracy. Pyth’s data providers are active participants in price discovery: they truly know the prices of assets. Pyth is designed to incentivize these data owners to contribute their private price data and aggregate these inputs to yield an accurate, representative snapshot of the markets.Transparent Aggregation—The Pyth Network’s aggregation mechanism is designed to be transparent and verifiable. The provenance of each data point can be traced back to the public keys of the data providers. The aggregation and delivery process is publicly auditable using widely available tools like the Solana block explorer and the Pyth Publisher Metrics.Reputational Alignment—Pyth’s data providers include established businesses in the traditional finance world and the blockchain industry. It is against their economic interest to attempt to influence the oracle unfairly, as their price inputs are public and they would incur reputational loss to their main commercial activities. In addition to this alignment is the aggregation mechanism, which prevents a minority of data providers from tampering the price.Ecosystem and GovernanceThe Pyth Network ecosystem spans a diverse range of stakeholders, from data owners to decentralized applications to individual blockchain participants. On-chain governance is critical for a protocol’s self-sustainability and decentralization. As discussed in a previous blog on the Pyth Network’s tokenomics, governance structures are generally established to enable community guidance of a protocol’s development.Governance is expected to be responsible for actions such as determining the parameters of update fees, the reward distribution mechanism for data providers, and determining how products are listed on Pyth and their reference data. You can read the whitepaper to learn more.SummaryThe Pyth Network contributors understood that past oracles were founded on a mistaken assumption on how financial data works. Legacy oracles served the nascent stages of DeFi well. But they also admitted of limitations in latency, asset coverage, and data quality, which restricted DeFi’s growth.The future of price oracles is not searching for and bringing prices to the blockchain: it is bringing price owners and creators to DeFi. The Pyth Network’s Pull Oracle architecture addresses these core limitations.The Pyth Network’s products are permissionless, transparent, low-latency, high-fidelity, and are designed to scale with the growth of Web3 itself. We’re excited for you to join the Pyth Network journey. There’s much to build.You can become a member of the Pythian community and explore the official social network channels. Stay tuned on the network developments and announcements: get the news and listen to our contributors speak on the latest podcasts and keynotes.Last Updated: Nov 4, 2023.We can’t wait to hear what you think! Feel free to join the Pyth Discord and Telegram, and follow Pyth on X. You can also learn more about Pyth here.Stay Updated with PythStay informed about Pyth network's development and upcoming
                  events!subscribeRecommended For Youall posts20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread more20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread more20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread morePrice Feeds Benchmarks Publishers Consumers Node Providers About Stats Ranking Developers Documentation Media Room Blog Jobs Disclaimer Brand Assets Blockchain Guides Data Driven Press Comparison  Bug Bounty Security Audits Contact Airdrop © 2023 Pyth Data AssociationPrivacy PolicyTerms of Use

URL: https://pyth.network/whitepaper_v2.pdf?ref=pyth-network.ghost.io
P Y T H N E T W O R K : A
F I R S T- PA R T Y F I N A N C I A L
O R A C L E
pyth data association
version 2.0
September 28, 2023
Financial market data is often only accessible to a limited set of institutions and
users. Traditional markets typically maintain strict control over live and historical
price feeds. Cryptocurrency markets currently have fewer barriers, although there
is no guarantee this arrangement will continue. Consequently, only a selected group
of users has access to the most timely, accurate, and valuable information.
The Pyth network aims to bring this valuable financial market data to DeFi applications and the general public. The network does so by incentivizing market
participants — trading firms, market makers, and exchanges — to share the price
data collected as part of their existing operations. The network aggregates this
first-party price data and publishes it on-chain for use by either on- or off-chain
applications.
The original whitepaper proposed an initial protocol design focused on the Solana
blockchain. This second version updates the design to reflect the current status of
the Pyth ecosystem. In particular, this version describes a novel cross-chain model
for price delivery to target chains.
The Pyth Data Association (the “Association”), in collaboration with the community of Pyth network participants, has published this whitepaper to describe the
current state of the Pyth network.
1 overview
The Pyth protocol is designed to incentivize participants to continually publish price
updates for various products (such as BTC/USD). Each product has a price feed
that continually updates with its current price and a confidence interval representing the estimated uncertainty of the price. For example, the current BTC/USD feed
may say the price is $65000 ± $50. The feed for each product is published on-chain,
where it is read by consumers, who may be either blockchain-enabled programs (on
various blockchains) or off-chain applications. An on-chain program produces the
price feed for each product by aggregating the price feeds of individual publishers.
The protocol is designed to attract publishers who are first-party data providers
with the ability to source high-quality, timely pricing information.
Thus, the protocol has two different sets of participants:
• Publishers publish price feeds and earn fees in exchange. Publishers are typically market participants with access to accurate and timely price information.
• Consumers read price feeds and incorporate data into smart contracts or
dApps. In the process, consumers pay fees to the protocol to access the data.
1
cross-chain architecture 2
Fees are charged at a fixed rate per Pyth price update on a target chain –
e.g., 0.0001 ETH per update. Consumers are users of on-chain protocols that
integrate Pyth for market data. These protocols may be running on various
blockchains.
To make Pyth prices available to a wide range of consumers, the protocol must
operate over multiple blockchains. The Pyth protocol uses an appchain called Pythnet to store and update the state of each price feed. Pythnet is a proof-of-authority
blockchain where each publisher runs a validator. Pyth prices are broadcast from
this appchain to other target chains by way of a cross-chain architecture that uses decentralized cross-chain messaging protocols, such as the Wormhole network. Broadcasting data from Pythnet makes it easy for the protocol to support a large number of target chains, thereby enabling consumers to use Pyth data no matter what
blockchain they are on.
Within this architecture, the aforementioned participants will interact via two
mechanisms. Both of these mechanisms will be implemented on one of the various
chains detailed above:
• Price aggregation combines the price feeds of individual publishers into a single price feed for the product. This mechanism is designed to produce robust
price feeds, that is, feeds whose prices cannot be significantly influenced by
small groups of publishers. This mechanism runs on Pythnet as an on-chain
program.
• Pyth Governance determines high-level parameters of the other mechanisms.
A critical challenge is designing these mechanics to be robust to various forms of
price manipulation. Two specific attacks to consider are:
1. Participants could onboard as publishers and attempt to manipulate the oracle price. The price aggregation mechanism is designed to guard against
this attack by limiting the influence of publishers on the aggregate price. Furthermore, the community will determine how publishers are permitted to use
the protocol and can choose to limit the set to highly reputable and honest
participants.
2. Bad actors could try to move prices on exchanges to influence the aggregate
Pyth price. Robustness in the price aggregation and a diversity of publishers
sourcing from different exchanges can decrease the risk of price manipulation
efforts.
2 cross-chain architecture
Pyth features publishers who provide price data on Pythnet, where the aggregation
mechanism (described in the next section), produces aggregate prices. The aggregated prices are subsequently broadcast and transferred to other blockchains where
consumers can use them. Pythnet is an application-specific blockchain on which
the only programs and activity are related to price publishing, aggregation, and initiation of the transfer to other blockchains. Pythnet’s consensus model and runtime
are based off of those of Solana.
A successful cross-chain architecture must achieve several important properties:
1. Minimize transaction costs. Maintaining price feeds on multiple blockchains
requires paying transaction costs (i.e., gas) on every single chain. The resulting
cost could be too expensive for the participants to bear.
2. Support high-frequency and low-latency price updates. These two properties are essential for applications that require timely price information.
cross-chain architecture 3
3. Scale to many blockchains. There are use cases for prices on different blockchains
that feature a diversity of runtimes, cosnensus models, and gas costs. If crosschain transfer of price data is too expensive, it will not be possible to reach all
these chains.
4. Scale to many price feeds. The Pyth protocol should scale to support price
feeds for a wide range of crypto and non-crypto assets. As with scaling to
many blockchains, cross-chain transfer of price data being too expensive will
inhibit reaching this scale.
The cross-chain architecture is a “pull” oracle that addresses these challenges
using a three-part workflow. The first part of the workflow is publishing prices
on chain efficiently and cheaply. In contrast to generalized blockchains that can
feature high gas costs, on Pythnet, permissioned publishers are able to publish
their updates for free. These permissioned publishers can submit price updates
with a valid price and confidence to the on-chain oracle program, which stores their
values in their field of the corresponding on-chain price account. When invoked,
the oracle program carries out aggregation on the prices in the price account (see
Section 3 for more details).
The second part is a price broadcast operation performed by the Pythnet validators as part of Pythnet consensus. After the oracle program aggregates publishers’
prices into an aggregate price for each of the price feeds updated in a slot, it calls
into the message buffer program with the aggregate prices of the updated price
feeds. The message buffer program allows for the creation of a message to be sent
to other chains and can be called by authorized programs. Here, the message buffer
stores the aggregate prices of the updated price feeds. Next, the validator reads the
message buffer’s accounts and constructs a merkle tree with the aforementioned
prices as the leaves of the tree. It then broadcasts the root of the tree to other chains
using a cross-chain messaging protocol, such as the Wormhole network. The Wormhole network is a decentralized cross-chain messaging system that enables data on
one blockchain to be read on other chains. The broadcast operation is intended to
be invoked at a high frequency, essentially at the frequency of the Pythnet blocktime. The output of this broadcast is a stream of attested merkle tree roots that
are available via the cross-chain messaging infrastructure and the data of the trees
themselves publicly visible on Pythnet for a rolling window of historical slots.
The third part is relaying, which occurs on a target chain where Pyth prices are
available. Each target chain has a Pyth receiver contract which stores a price for
every Pyth price feed. These contracts implement a permissionless operation to
update the stored price. The input to this operation is an attested merkle tree root,
a price update for a particular symbol that represents a leaf in the corresponding
merkle tree, and the path in the tree that leads from that leaf to the root. The latter
two can be accessed publicly on Pythnet. The operation performs various checks on
the message (e.g., to validate signatures, to validate the root-leaf-path combination);
if the update is valid, the new prices are stored in the Pyth receiver contract.
Consumers of Pyth prices are responsible for invoking the permissionless price
update, i.e. pulling the price update on chain, before using the price. The price
stored in the Pyth receiver contract grows stale over time unless it is updated. Protocols integrating with Pyth price feeds can impose a limit on the maximum staleness of the price. Anyone interacting with one of these protocols will therefore
be required to invoke the permissionless price update before their interaction if the
current on-chain price is stale.
In this design, consumers pay the transaction costs for updating Pyth price feeds
only when the price is needed. This property is how the cross-chain architecture meets
the goals set forth above. The broadcast component can stream high-frequency
price updates for many different price feeds without incurring any transaction costs.
Many of these price updates will never land on a target chain (and therefore never
price aggregation 4
incur a transaction cost). Target chain transaction costs are themselves minimized
because consumers only incur them when they need to use a price for an operation.
2.1 Update Fees
Consumers are required to pay an update fee to the protocol in order to invoke the
price update operation on a Pyth receiver contract. Fees are charged in the native
token of the target chain.
2.2 Comparison: Pull vs. Push
Most oracles have traditionally used a push architecture. In this architecture, the
oracle publishes prices onto a general-purpose blockchain, and may even perform
aggregation on that chain. The oracle is responsible for keeping prices fresh, and
therefore must regularly send transactions to update the on-chain price. These
transactions incur gas costs that scale with update frequency and the number of
supported price feeds, blockchains, and possibly even publishers. Moreover, these
oracles can be unreliable, as their price update transactions compete with other network activity. During busy periods, network congestion can prevent oracle updates
from landing on-chain.
Unlike the push model, Pyth’s pull model features price publishing and aggregation on a cheap chain. Pythnet is a fork of Solana, which allows for low-latency and
high-frequency price updates. Pythnet transactions are free for publishers, which
significantly lowers the overall operating costs of the oracle. Broadcasting prices
to other blockchains still carries gas costs. However, unlike the push model where
updates are pushed (and gas is paid) irrespective of demand, Pyth only pays gas
when consumers demand a price update. As a result, gas consumption is more targeted and efficient. Consequently, Pyth can have more frequent price updates, and
scale to more price feeds and blockchains than push oracles. The pull model is also
not prone to unreliability. Network congestion on target chains does not affect the
ability of publishers to publish prices to Pythnet, and motivated users can always
pull a price from Pythnet on to their target chain by paying a sufficient transaction
fee.
Another advantage of Pyth’s architecture is its ability to handle stateful computations like exponentially-weighted moving averages (EMAs). These computations
are time-weighted combinations of previously published data. Push oracles struggle to compute such combinations on-chain, as their low update frequency produces
coarse temporal samples. For instance, it is difficult to construct a 5-minute EMA
when the update frequency is 10 minutes. In contrast, Pyth has access to price updates every 400 ms on Pythnet, which easily allows it to construct EMAs and other
temporal combinations.
3 price aggregation
The price aggregation mechanism combines each individual publisher’s price and
confidence feed into a single aggregate price and confidence feed. For example, one
publisher may say that the price of BTC/USD is $52000 ± 10 and another that it is
$53000 ± 20, and price aggregation may combine these two prices into an aggregate
price of $52500 ± 500. This mechanism is part of the on-chain program and triggers when publishers submit price updates: the first price update on a given slot
automatically aggregates the prices from the previous slot.
The price aggregation algorithm is designed to have three properties:
1. It is resistant to manipulation — both accidental and intentional — by publishers. For example, if most publishers submit a price of $100 and one publisher
price aggregation 5
Figure 1: Scenarios for the aggregation procedure. The lower thin bars represent each publisher’s prices and confidence intervals, and the bold red bar represents the resulting aggregate price and confidence.
submits a price of $80, the aggregate price remains near $100. This property
increases the likelihood that the aggregate price remains accurate even if a
small percentage of publishers submit a price far from the market. Figure 1(a)
depicts this scenario.
2. The aggregate price appropriately weights data sources with different levels of
accuracy. The Pyth protocol allows publishers to submit a confidence interval
because they have varying levels of accuracy in observing the price of a product. For example, some publishers are expected to be exchanges. Exchanges
have different levels of liquidity, and less liquid exchanges tend to have wider
bid/offer spreads than more liquid ones. This property can result in situations
where one exchange reports $101 ± 1, and another reports $110 ± 10. In these
cases, the aggregate price is closer to $101 than $110. Figure 1(b) depicts this
scenario.
3. The aggregate confidence interval reflects the variation between publishers’
prices. In real-world markets, there is no single price for any given product.
Products trade at slightly different prices at various venues at any given time.
Furthermore, the product’s spread is a fundamental limit on the precision
of the product’s price. The aggregate confidence interval reflects both the
variation across venues and these limitations. Figures 1(c) and (d) depict two
different cases where there are price variations across exchanges.
The price aggregation algorithm uses a variant of the weighted median. An input
to the algorithm is a stake-weight for each publisher. These weights will initially
be set uniformly, but in the future may be set using additional mechanisms (such
as data staking from the original whitepaper) as determined by the community.
The first step of the algorithm computes the aggregate price by giving each publisher three votes – one vote at their price and one vote at each of their price plus
and minus their confidence interval – then taking the stake-weighted median of
the votes. The second step computes the distance from the aggregate price to the
stake-weighted 25th and 75th percentiles of the votes, then selects the larger as the
aggregate confidence interval.
This simple algorithm is a generalization of the ordinary median. Most people understand the median as the middle value in the data set, that is, the 50th percentile.
However, the median is also the value R that minimizes the objective function
∑i
|R − pi
| where pi
is the price of the ith publisher. This function penalizes R based
on its distance from the publisher’s price pi
. The proposed algorithm computes the
aggregate price R that minimizes 1
3
Σi
si
|R − pi
| + 2
3
Σi
si max(|R − pi
| − ci
, 0), where
si
is the publisher’s stake-weight and ci
is the publisher’s confidence interval. This
objective does two different things. First, it weights publishers according to their
stake, such that low-stake publishers have minimal influence on the price. Second,
it combines the ordinary median objective with a second term that only assigns a
penalty to R if it lies outside the publisher’s confidence interval.
governance 6
4 governance
On-chain governance is expected to be responsible for taking the following actions:
• Determining the size of update fees.
• Determining the reward distribution mechanism for publishers.
• Approving other software updates to on-chain programs across blockchains.
• Determining how products are listed on Pyth and their reference data (e.g.,
number of decimal places in the price, reference exchanges).
• Determining how publishers will be permissioned to provide data for price
feeds
5 token distribution
Unlocked Locked Total
Publisher Rewards 0.5 21.5 22
Ecosystem Growth 7 45 52
Protocol Development 1.5 8.5 10
Community and Launch 6 0 6
Private Sales 0 10 10
Total 15 85 100
Table 1: Allocation of locked and unlocked PYTH tokens. Locked tokens unlock 6, 18, 30
and 42 months after token launch.
There are 10,000,000,000 PYTH tokens and this total supply will not increase.
Furthermore, 85% of the tokens are initially contractually locked. Locked tokens
unlock 6, 18, 30, and 42 months after token launch. This schedule is designed to
produce a gradual increase the unlocked token supply over time. The remaining
15% of PYTH tokens are initially unlocked. The supply of both locked and unlocked
tokens are allocated per the categories shown in 1.
6 conclusion
This whitepaper proposes an oracle protocol to make accurate, high-resolution financial market data easily accessible on-chain. The protocol is designed to be a selfsustaining decentralized network that coordinates data publishers and consumers.
The protocol is designed to attract publishers with high-quality pricing data, and
incentivizes these publishers by paying them fees collected from consumer usage of
the data. The mechanisms help prevent malicious attackers from manipulating the
protocol to their benefit in various ways, such as manipulating the price.



URL: https://pyth.network/blog/understanding-the-pyth-tokenomics
Understanding the PYTH Tokenomics | Pyth NetworkProducts Price FeedsReal-time prices for smart contractsBenchmarksHistorical Pyth market dataEcosystem Explore the EcosystemMeet Pyth UsersCommunity HubSee Data ProvidersBecome a Data ProviderPyth StatsDune DashboardDevelopers DocumentationStart integrating Pyth data feedsGet StartedHow Pyth Works On-Demand Updates Pythnet Price Feeds TradingView Integration TutorialsIntegrate on EVM (On-Demand) Integrate on EVM (Pusher) Integrate on Solana Integrate on Other Chains Price Feed IDsGitHubResources Get in TouchResourcesPodcastsVideosNewsUse CasesCareersData Driven 2023Blog Products Price FeedsReal-time prices for smart contractsBenchmarksHistorical Pyth market dataEcosystem Explore the EcosystemMeet Pyth UsersCommunity HubSee Data ProvidersBecome a Data ProviderPyth StatsDune DashboardDevelopers DocumentationStart integrating Pyth data feedsGet StartedHow Pyth Works  On-Demand UpdatesPythnet Price FeedsTradingView IntegrationTutorialsIntegrate on EVM (On-Demand)Integrate on EVM (Pusher)Integrate on SolanaIntegrate on Other ChainsPrice Feed IDsGitHubResources Get in TouchResourcesPodcastsVideosNewsUse CasesCareersData Driven 2023Blog Privacy PolicyTerms of Use back17 Oct 20234 min readUnderstanding the PYTH TokenomicsShare:This blog post delves into the PYTH Token distribution to different participants of the Pyth Network and its ecosystem. This distribution is a pivotal step towards bringing the Pyth Network to a decentralized, self-sustainable, and permissionless state. On-chain governance is another critical component of this goal.The general purpose of a token-based governance system is to enable token-holders to guide protocol development. It is therefore important that the community can prepare to participate in token-holder governance so that they can shape the network in an informed manner.Scope of Governance and the Pyth DAOAs stated in the whitepaper, Pyth Governance can help determine high-level parameters of the other network mechanisms. On-chain governance is expected to be responsible for many decisions and actions, such as:Determining the size of update fees.Determining the reward distribution mechanism for data providers.Approving other software updates to on-chain programs across blockchains.Determining how new symbols (feeds) are listed on Pyth and their reference data (e.g. the number of decimal places in the price, reference exchanges).Determining how data providers will be permissioned to provide data for price feeds.Note that new topics, with respect to on-chain governance, may be established by the DAO.Token DistributionToken Symbol: PYTHMax Supply: 10,000,000,000Initial Circulating Supply: 1,500,000,000 (15%)Vesting: 85% of the PYTH Tokens are initially locked and locked tokens will unlock 6, 18, 30 and 42 months after the initial token launch.Token AddressDistributionBelow is the PYTH Token distribution table as per the whitepaper.Publisher Rewards22% — 2,200,000,000 PYTHThis allocation is reserved for the Pyth Network data providers, or "publishers".The publishers are responsible for publishing price data to the Pyth Protocol. The “Publisher Rewards” allocation consists of reserved tokens for various reward mechanisms and grant programs to encourage publishers to publish accurate and timely price data.This is designed to encourage more publishers to support new symbols which may lack the initial popularity or liquidity for the network to launch immediately.There are already rewards mechanisms and grant programs in place to incentivize publishers to publish price feeds so that the Pyth Protocol can provide accurate and timely price updates.~2% (50M) of the 2.2B PYTH Tokens are unlocked. The remaining PYTH Tokens (2.15B) are subject to the vesting schedule described above. Note that these rewards can only be distributed to publishers once they are unlocked.Ecosystem Growth52% — 5,200,000,000 PYTHThe “Ecosystem Growth” allocation is a strategic portion of tokens set aside for contributors to the Pyth Network, including developers, educators, researchers, strategic contributors, early publishers, and more.This allocation aims to facilitate practical initiatives including funding research projects aimed at advancing the Pyth Protocol, incentivizing developers to build complementary tooling and resources, and supporting public education programs to increase awareness. This allocation aims to recognize and reward individuals and organizations that go beyond the core contributors in fostering the expansion and vitality of the Pyth Network.13% (700M) of the 5.2B PYTH Tokens are unlocked. The remaining tokens (4.5B) are subject to the unlock schedule described above.Protocol Development10% — 1,000,000,000This portion of the token supply has been allocated to core contributors focused on building oracle tooling, products, and infrastructure to expand the protocol’s suite of decentralized data services, such as Douro Labs.15% (150M) of the 1B PYTH Tokens are unlocked. The remaining tokens (850M) are subject to the unlock schedule described above.Community and Launch6% — 600,000,000This portion of PYTH Tokens is set aside for the initial launch phase and related activities and initiatives.All 600M PYTH Tokens of “Community and Launch” allocation will be unlocked from day one.Private Sales10% — 1,000,000,000This category represents two historical funding rounds to strategic contributors who add value to the network in terms of advisory and infrastructure support. Please note that these funding rounds closed and the allocation has been finalized.All of 1B PYTH Tokens are locked and subject to the unlock schedule described above.There are currently no announcements regarding PYTH Governance. You can stay updated on the Pyth Network’s developments through the official social media channels. We highly recommend that readers exercise caution and take appropriate measures to protect themselves from unverified or unofficial channels and claims.We would like to express our appreciation to the Pythian community for their patience and continued support throughout the years.We can’t wait to hear what you think! Feel free to join the Pyth Discord and Telegram, and follow Pyth on X. You can also learn more about Pyth here.Stay Updated with PythStay informed about Pyth network's development and upcoming
                  events!subscribeRecommended For Youall posts20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread more20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread more20 Nov 20233 min read Permissionless Mainnet & Token-Led Governance are Liveread more20 Nov 20235 min read Guide to Claiming Your Retrospective Airdrop Allocationread more14 Nov 20232 min read Pyth Price Feeds Launch on Coreread more13 Nov 20232 min read Pyth Price Feeds Now Available on ZetaChainread more09 Nov 20232 min read Pyth Price Feeds on NEAR Testnetread more08 Nov 20233 min read Pyth Monthly Update | October 2023read more06 Nov 20232 min read Pyth Price Feeds Now Available on Chiliz Chainread morePrice Feeds Benchmarks Publishers Consumers Node Providers About Stats Ranking Developers Documentation Media Room Blog Jobs Disclaimer Brand Assets Blockchain Guides Data Driven Press Comparison  Bug Bounty Security Audits Contact Airdrop © 2023 Pyth Data AssociationPrivacy PolicyTerms of Use

URL: https://www.bloomberg.com/press-releases/2023-08-29/douro-labs-launches-and-joins-pyth-network-as-core-contributor
Douro Labs Launches and Joins Pyth Network as Core Contributor
29 August 2023 at 20:00 GMT+8
Share this article

Gift this article
  Douro Labs Launches and Joins Pyth Network as Core Contributor

Douro Labs Joins Network to Work on Perseus Upgrade as well as Permissionless
                      Mainnet with Token-Led Governance

Business Wire

PORTO, Portugal -- August 29, 2023

Douro Labs, a software development company dedicated to advancing the Pyth
Network, officially launches today and is excited to be joining the network as
the latest core contributor. The Pyth Data Association and the Pyth Network’s
community includes a vast network of data contributors including top trading
firms, leading exchanges, and premier crypto companies globally including Cboe
Global Markets, Optiver, IMC, Flow Traders, OKX, Bybit, Wintermute, QCP
Capital, Auros, Susquehanna International Group, and LMAX. The Douro Labs
entity will initially work to implement the Perseus Upgrade and bring the
network into a permissionless mainnet with token-led governance for the fall
of 2023.

Pyth Network is the largest first-party oracle for financial data. Oracles are
programmatic data feeds that bring off-chain data on-chain for smart contracts
to use. They are an essential component of decentralized finance (DeFi). The
Pyth Network provides low-latency, high-fidelity, and tamper-resistant price
data feeds directly to blockchains through a vast network of first-party data
providers.

“We are thrilled to welcome Douro Labs as the newest contributor to the Pyth
Network,” said Marc Tillement, Director at Pyth Data Association. “The Pyth
Data Association was formed with a mission to create the largest, most robust
financial data marketplace for decentralized finance to build on. Thanks to a
diversity of contributors and a growing ecosystem of users, the Pyth Network
has quickly become the largest first-party oracle network.”

Douro Labs was formed by long-time Pyth Network contributors Mike Cahill,
Jayant Krishnamurthy, and Ciaran Cronin in July 2023. The company employs
close to 20 individuals who previously worked at firms such as Goldman Sachs,
Jump Crypto, BNP Paribas, Amazon Web Services and Chorus One. The company is
focused on contributing alongside other data providers and building
developer-focused oracle tooling and core protocol infrastructure.

“The Pyth Network is the fastest growing decentralized oracle, and is already
becoming the go-to solution for modern DeFi applications that need cheap,
lightning-fast, ultra-accurate pricing information,” said Mike Cahill, CEO of
Douro Labs. “At Douro Labs, we are committed to accelerating the network’s
continued growth and lifting up the next generation of DeFi apps that are
building new tools and experiences that simply aren’t possible on legacy
oracle infrastructure.”

“As one of the founding institutional data providers on the Pyth Network, we
are pleased to see the formation of Douro Labs as a dedicated blockchain
infrastructure company,” said David Mercer, CEO of LMAX Group. “We look
forward to supporting Douro Labs as it accelerates the development of this
transformative and fundamental building block of the new financial
infrastructure for both DeFi and TradFi. This expansion of capability
underscores the value of democratizing the distribution of readily available,
real-time and verifiable market data.”

First-generation oracles rely on networks of third-party operators to source
and aggregate pricing data, which is typically achieved through unauthorized
scraping. Pyth Network's model eliminates slow, unreliable third-party data
aggregators and replaces them with fast, first-party data providers, such as
trading firms, exchanges and brokerages.

“Auros is thrilled to see the formation of Douro Labs, which furthers the
mission of Pyth Network to democratize high-fidelity market data for all
blockchain participants. The Auros team is a proud supporter of Pyth's
vision,” added Ben Roth, co-founder and CIO of Auros. “Together with the
talented individuals at Douro Labs, we are committed to contributing to the
advancement of Pyth's decentralized oracle solutions and the growth of the
blockchain and Web3 ecosystem.”

The Pyth Network supports more than 300 sub-second price feeds across major
asset classes including digital assets, equities, ETFs, FX and commodities.
Additionally, over 180 DeFi and CeFi applications use the Pyth Network,
including projects like Synthetix, Venus, Ribbon Finance, Vela Exchange, and
Solend, as do more than 30 blockchains, including but not limited to Ethereum,
BNB Chain, Arbitrum, Optimism, Base, Solana, Injective, zkSync Era, Fantom,
Osmosis, Aptos, Sei, Aurora, and Sui.

“Making market data accessible to investors has always been a core focus for
us at IEX,” said Ronan Ryan, President of IEX Group. “We look forward to
seeing how the talented team behind Douro Labs will add the tooling and
infrastructure needed to make the Pyth Network a go-to market data solution.”

To join the Pyth Network and become a data provider, please get in touch at
pyth.network. If you’re interested in building applications on top of the
world's fastest-growing, most innovative oracle, get started in docs at
docs.pyth.network/documentation.

About Pyth Network
The Pyth Network is the largest first-party oracle for the world’s financial
data. It supports more than 300 real-time price feeds across major asset
classes including digital assets, equities, ETFs, FX, and commodities. The
network comprises some of the world's largest exchanges, market makers, and
financial services providers contributing their proprietary price data
on-chain for aggregation and distribution to smart contract applications.
Thanks to the Pyth Network’s innovative pull oracle design, applications can
effortlessly "pull" the latest price onto their native blockchain on demand.
In less than a year since the launch of its cross-chain pull model, the
network has secured over $1B in total value. The Pyth Network has been used by
DeFi protocols in over $65B in trading volume and in over 180 applications.
You can learn more about the Pyth Network here and its documentation.

About Douro Labs
Douro Labs is a blockchain infrastructure company that contributes to the
development and acceleration of the Pyth Network, the largest first-party
financial oracle network for delivering real-time financial market data to
smart contracts applications. Established in 2023, Douro Labs is building
oracle tooling, products, and Web3 infrastructure that will expand the Pyth
Network's suite of decentralized data services and enhance access to
real-time, once-exclusive market data for all blockchain participants. To
learn more about Douro Labs, please visit http://dourolabs.xyz/.

About Pyth Data Association
The Pyth Data Association is a Swiss association founded by Pyth Network
participants to advance the development of the network. The Pyth Data
Association is a contributor to the Pyth Network and helps facilitate protocol
maintenance, ecosystem grants, and ecosystem development. To learn more about
the association, please visit https://pythdataassociation.com/.


Bloomberg - Are you a robot?









Bloomberg
Need help? Contact us


We've detected unusual activity from your computer network
To continue, please click the box below to let us know you're not a robot.




Why did this happen?
Please make sure your browser supports JavaScript and cookies and that you are not
            blocking them from loading.
            For more information you can review our Terms of
                Service and Cookie Policy.


Need Help?
For inquiries related to this message please contact
            our support team and provide the reference ID below.
Block reference ID:






URL：https://docs.pyth.network/documentation/how-pyth-works
Design Overview
Pyth is a protocol that allows market participants to publish pricing information on-chain for others to use. The protocol is an interaction between three parties:

Publishers submit pricing information to Pyth's oracle program. Pyth has multiple data publishers for every product to improve the accuracy and robustness of the system.
Pyth's oracle program combines publishers' data to produce a single aggregate price and confidence interval.
Consumers read the price information produced by the oracle program.
Pyth's oracle program runs simultaneously on both Solana mainnet and Pythnet. Each instance of the program is responsible for its own set of price feeds. Solana Price Feeds are available for use by Solana protocols. In this case, since the oracle program itself runs on Solana, the resulting prices are immediately available to consumers without requiring any additional work. Pythnet Price Feeds are available on 12+ blockchains. The prices constructed on Pythnet are transferred cross-chain to reach consumers on these blockchains.

In both cases, the critical component of the system is the oracle program that combines the data from each individual publisher. This program maintains a number of different Solana accounts that list the products on Pyth and their current price data. Publishers publish their price and confidence by interacting with the oracle program on every slot. The program stores this information in its accounts. The first price update in a slot additionally triggers price aggregation, which combines the price data from the previous slot into a single aggregate price and confidence interval. This aggregate price is written to the Solana account where it is readable by other on-chain programs and available for transmission to other blockchains.



