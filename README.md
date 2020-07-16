tags: Project HackFS-linchpin : Working Group Notes


# Open Developer Call - 07/16/2020

## Info:

Current Timeslot: 
8:00 AM - PST 

[(Base code for iteration)] [https://etherscan.io/address/0x56074ac10eef4c63428e0be4853e5bcfebd42bd0#code](https://etherscan.io/address/0x56074ac10eef4c63428e0be4853e5bcfebd42bd0#code)

[(Base code for iteration - comments removed )] [https://gist.github.com/tenfinney/003fd7c6212d2c9ec6f2720ae6bc14c2](https://gist.github.com/tenfinney/003fd7c6212d2c9ec6f2720ae6bc14c2)

[(Location Video/Screenshare:)] [https://us02web.zoom.us/j/6966768498](https://us02web.zoom.us/j/6966768498)

[(CryptoVoxels (2D VR):)] [https://www.cryptovoxels.com/play?coords=N@306E,105S](https://www.cryptovoxels.com/play?coords=N@306E,105S)





# HACKFS 2020 - IDEATION PHASE

## Buckets or Threads? Served Hot or Cold? Naked or Cloaked? Content Restricted or Open Gateway? 

### Public Data vs Encrypted Private Data poses a myriad of questions regarding content subject matter and privacy concerns. Each use-case user and miner will have to make market decisions.

- The network is hard drives and ram.  Hot and cold storage and a payment layer for storage negotiation
   -[]  Is IPFS a superior solution to Ethereum or a valuable complement to it?
   -[]  It is unfeasible to manage the high-demand load of transactions on the current public Ethereum based on the physical requirements or serving content. Therefore it has to operate as a side-rail protocol but it needs a blockchain-style integration to manage the miner rewards for sserving the data. Filecoin
   -[]  Sometimes we want an NFT, or othertimes a .vox file, or maybe just access to a image or text file, a document, or video. Maybe you need a JSON file to run commands. Even smart contract and ABI and all sorts of encrypted private information too.
   -[]  One of the greatest features of IPFS is it’s flexibility. However, storing digital files is not completely free.
   -[]  The cost of production is benefit of a transactional service in Filecoin the sdtorage there are interesting opportunities. Greate a group around the economy of digital evidence in court cases, The Evidencer value is the transaction of the persistent and consistence availability of content storage.
   -[]  Should we use the logs on Ethereum?
   -[]  Logs are an elegant way to store tiny amounts of data on the Ethereum blockchain for a small price. Specifically, event logs are useful to let other people know something has happened without them having to query contracts individually.
   -[]  https://medium.com/mycrypto/understanding-event-logs-on-the-ethereum-blockchain-f4ae7ba50378
   -[]  Logs - Wood, G. (2014). Ethereum: A secure decentralised generalised transaction ledger
   -[]  Logs - Ethereum Foundation. (2016). Solidity Documentation
   -[]  Content storage tradeoffs. IPFS data is having to store data 1. in the clear and one with encoding on it.  There are reasons for making this slower and better characteristics.  The verified slowers create a more redundant second copy just in case.  Now its just pragmatic to do it. Go for security now and see if we can get to efficiency.
   -[]  Focus on computation that is public by default. If you don’t have to worry about privacy you can use the files as computational hubs to run code and interoperate with other systems and blockchains. Verifiability becomes cheap. All you have to do is run a trace around the computation which you can always replay it later, like in CryptoVoxels. 
   -[]  And we constantly move between content management for storing files and blockchain for executing on chain tasks and storing records on a public blockchain.
   -[]  A key point in the above definition is multi-tiered. Basically Powergate has hot and cold tiers of storage with IPFS nodes acting as the hot caching layer, and Filecoin serving as the cold persistance layer.
   
   ![](https://i.imgur.com/Gn8QEJ2.png)

   
### IPFS vs Ethereum and why use bridging?
   -[]  Biconomy - Scalable Relayer Infrastructure for Blockchain Transactions.
   -[]  Bridging will need to take place on ethereum or other chains because IPFS/FileCOin needs to release with core component ans let the rest follow.  see: exaples here https://github.com/filecoin-project/specs-actors/blob/master/actors/builtin/multisig/multisig_actor.go https://github.com/filecoin-project/specs-actors/tree/master/actors/builtin/paych https://github.com/filecoin-project/specs-actors/blob/master/actors/builtin/account/account_actor.go 
   -[]  The CID is the Linchpin
   -[]  The CID is a tool used to verifier the location and the veracity of data.
   -[]  IPFS CID (address to some data, file or folder) input. CID based management
   -[]  Logs - Ethereum Foundation. (2016). Web3 Documentation
   -[]  A CID is a self-describing content-addressed identifier for distributed systems. 
   -[]  They are multi protocol, meaning you can use them and get IPFS hashes, IPNS addresses, and ThreadDBs all at the same time.
   -[]  A database index allows a query to efficiently retrieve data from a database.  Indexes are related to specific tables and consist of one or more keys. 
   -[]  Indexes are used to quickly locate data without having to search every row in a database table every time a database table is accessed.
   -[]  In IPFS the CID is a powerful index. It keeps track of the content of the file, the locaton of the file, ensures the integrity of the file, can be universally available and also gated.  
   
   ![](https://i.imgur.com/A9AyTVq.png)

### Considerations in submitting a project to HackFS
   -[]  Sponsors IPFS Filecoin ENS MetaMask Inura Textile 3Box Fleek Pinata Biconomy
   -[]  We also have integrated the sponsors into the solution to show typical users the wide spectrum of products being built that bridge IPFS through the public Ethereum blockchain and vice versa. We will start with purely public transactions, ones that do not need to be encrypted. 
   -[]  Fist let’s consider the sponsors objectives. Do Protocol Labs and Consensys objectives align with ours? If not, a new strategy is in order. If they do, it in imparative to present a solution that they will see value from their own points of view.  For example, Tachyon by Consensys, is a  global network of experts and advisors who invest in core blockchain development and help guide founders in building validated, market-ready Web 3.0 businesses. So what is their interest in the HackFS> It is to find an idea to incubate it and the exploit it to maximize the profits just like any other for profit business.
   -[]  Companies often struggle to find top talent for innovation but then limit their autonomy, creating a vicious cycle, as firms that do not successfully address the autonomy-control challenge are bound to face difficulties in attracting and retaining the most creative workforce. These strategies can help break this cycle by diligently setting the stage before each innovation process instead of micromanaging it
   -[]  Hackathon organizers promote new ideas by removing themselves from providing feedback and creating a safe environment in which new ideas receive very early peer-to-peer feedback. This is done, in many hackathons, in the form of a first ideas kickoff session. A kickoff allows participants to be “on stage” presenting, articulating, and elaborating on the initial idea theyhave in mind to solve their challenge.
   -[]  Encouraging them to present and put their ideas onstage can help accelerate the innovation process. Creating a safe environment enhances the autonomy that employees feel to follow their curiosity and original thinking, while balancing the need to have an efficient learning and innovation process in the organization.
   -[]  Team member integrated demos - NFT42 InfiNFT MachiX MetaFactory Web3vm LexDAO
   -[]  The reason this is important is because talent is scarce in this new ecosystem.  For purely economic reasons the sponsor needs to get as close to the “next big thing” and there are not enough developers to react to every opportunity. That is why product selection may be the most important factor in deciding what the hach submission is.
   -[]  We willl move through a few use cases quickly form simple to more comlplex concepts of content and IPFS hashes. human readable text file to encrypted content
   
### Our main focus is the NFT space.
   -[]  Take an application like Charged particle. It’s a NFT presumably using a ERC721 standard. That means there is a URL in its schema.  Where is that URL pointing to?
   -[]  Our goal with this submission is to provide a framework with some mini applications that will be useful to the average consumer with little or no background in computer programming, cryptograhy, or complicated systems.
   -[]  Our target is a general user that wants a specific need met.
   -[]  Longevity of storage and speed of content delivery are two different business models and user needs.  Retrieval market in FileCoin is less focused on CDN right now. The prmitives exist but the other users will have to build it out.
   -[]  Let’s equate this application as a type of vending machine, one that provide self served delicious snack-contracts one that serve simple but crucial elements of a decentralized web.
   -[]  There are many interesting applications where one protocol can leverage another thus resulting in something possible greater than the individual applcations themselves.  Let’s take for example CrytoVoxels a 3D metaverse. A metaverse is a digital playground and CrytoVoxels extends and leverages Web3 technology to make the underlying game wore poperful and unlocks features thatcan be contemplated far outside the structure of the game itself.
   -[]  I hope to focus on local IPFS node rings using libp2p, buckets, FileCoin, some of my own NFT smart contracts and some pinning mechanisms.  Most likely the demo will take place in one of my CryptoVoxel metaverse parcels.
   -[]  Maybe a custodial key to decrypt it helps in a private trust ring-node network where it can’t be broken unless a court order or subpeona of proper jurisdiction of subject matter or person.
   -[]  What hasn’t been explored is using IPFS file and bucket schemas to conduct productive fun and games as well as business applications.
   -[]  Speed of light at home will be the most efficient. The CDN business are in that business of figuing out how close the data needs to be to the end user.
   -[]  Strong emphasis on managing the state of the lifecycle of data. i.e. do you want it to exist on IPFS or move it to a Filecoin deal?
   -[]  Strong emphasis on deal management: it will watch and ensure all the deals you request go through (e.g. 3 replications) and are kept alive as long as you need.
   
   ![](https://i.imgur.com/jfYZghz.png)

   
### Potential Use Cases to Focus the Submission
   -[]  Let’s focus on a few simple use case with IPFS.
   -[]  Each use-case will be abstracted to allow for different integration of IPFS FileCoin and libp2p technologies.
   -[]  Marketplaces
   -[]  Fully decentralized DApps - Why is this important?
   -[]  Certificates & Provenance
   -[]  Create a Node-Content Explorer
   -[]  Capture the Retrieval Market
   -[]  Offer Version Control Solutions
   -[]  Provide Hosted APIs
   -[]  Decentralized Website Hosting
   -[]  Pinning Services
   -[]  Trustless Data backups
   -[]  Local file system mounting
   -[]  Marketplace and registry for user data controlled applications.
   -[]  Peer to Peer file sharing selectively with other people and/or within teams.
   -[]  Retrieving audio tracks from IPFS
   
      
![](https://i.imgur.com/ChPikgw.png)

   
## EARLY OPTIONS DEMO
   -[]  Identity solution enabling users to be fully anonymous or have as many identity associations
   -[]  For example the Ethereum Name Service (ENS) is a powerful feature of Ethereum and operates as an independent entity. ENS allow for content hashes in IPFS to be referenced in the domains records.  We use the domain `sixfinney.eth` as an example.
   -[]  Another example is a business document that you need to permanently store like a business contract or a government for. This also does not need to be encrypted as they are intended for public use.
   -[]  We are using a sample lease agreement, but any type of form will do. We will represent it as a pdf file, but it can be a word document excel spreadsheet or any type of file.
   -[]  First you take the local file (one on your computer) and send it to IPFS to get the return hash. Then you pass that hash along to one of the nodes that is probably hosting that content. Here we use the IPFS gateway and the Infura gateway, and we can easily usae ARWEAVE and Pinata as additional pinning protocols
   -[]  Visualizer and dashboards with Filscan.io Filplorer.com Filscout.io


![](https://i.imgur.com/IDIi5wf.png)

   
   
## SAMPLE PRESENTATION CORE CONTENT
   -[]  Our presentation today starts flat and becomes more complex later with the implementation of buckets from textile, filecoin from protocol labs, and local-ring and routing using libp2p, pinata and fleek for post redundancy. 
   -[]  We will run our presentation in CryptoVoxles to demonstrate how common Ethereum and IPFS transaction happen in the metaverse.
   -[]  IPFS has no incentivized storage layer, Filecoin is incentivized storage. And Powergate provides a bridge
   -[]  Our smart contracts should support Native Meta Transactions so there there is no need to create a Web3 account ahead of time Biconomy Relayers can directly relay the transactions to an application contract. See Swag0x
   -[]  Payments only by approved erc20 digital token or transfer by debit card through Wyre gateway running in an iFrame.
   -[]  We can allow users to pay Ether gas fees but in other stable tokens and not the actual gas currency. This is usually applicable in decentralized finance applications. Meta Transactions can be done in two ways: Contract Based Web3 Accounts or Native Meta Transactions -  we will use javascript
   -[]  Native Meta Transactions Remove dependency on msg.sender and msg.value from smart contracts
   -[]  To perform meta-transactions, a user needs to sign a message. After a user signs it, DApp sends the message to a relayer who sends that message into an actual transaction to a public node so the transaction can be mined.
   -[]  EIP712 Standard for Signing Transactions This standard allows wallets to display data in signing prompts in a structured and readable format. EIP712 is a great step forward for security and usability because users will no longer need to sign off on inscrutable hexadecimal strings, which is a practice that can be confusing and insecure.
   -[]  Bare bones application that runs run a simple piece of javascript for trying some different retrieval strategies to their local ring or client. The user downloads a piece of code that is just a javascript where the user picks a strategy that works best for their content delivery needs. And that allows lots of people to make lots of dynamic decisions for a content delivery network. 
   -[]  We could benefit from a folder-like management system built on IPFS.
   -[]  Super easy to use Js library with easy to understand functions for File CRUD, Sharing, Identity, Backups, etc.
   -[]  You can perform any Create, Read, Update, Delete (CRUD) operation with the Space Client, such as adding files, opening files and managing the encrypted buckets in which your files reside. Each action interacting with files is interacting with client-side encryption methods and storing the files privately on IPFS and/or Filecoin. The files are stored locally on the users computer with utmost privacy and security. These operations are performed through the use of cryptographic keys.
   -[]  FileCoin
   -[]  The cost of content delivery storage is outpacing the cost of content storage so over time. Moving the content becomes the higher cost overtime because storage capacity in disks is outpacing the cost of delivering over cabels and wirelss infrastructure. This will result in people amassing large amounts of data they control and also take advantage of providing low cost storage for others that need it.
   -[]  Ex. 80% of purchase totals go to the creator, 10% maintaining the FC requirement to maintain the file on the network, and 10% divided by n where n is the number of NFT’s sold distributed to the token holders.
   -[]  Filecoin Collateral Loans to bootstrap miners to get involved in the market as it grows.
   -[]  These Filecoin Deals are contracts and there are real rules of the game.
   
   ![](https://i.imgur.com/Y3wPY2Q.png)

   
## PowerGate
   -[]  Filecoin network interaction for file storage and retrieval market.
   -[]  FFS (Filecoin File Storage) module
   -[]  Currently pure IFPS/IPNS/and HTTP Gateways
   -[]  https://medium.com/@samikshan/using-ipfs-filecoin-for-decentralised-storage-with-powergate-71ffe42f8c09
   -[]  Contract Based Accounts - In this approach, an upgradable Contract Wallet is created for each user which acts as a proxy contract for the user and all his transactions are routed via his contract wallet. User needs to store all his tokens and funds in his Contract Wallet.
   
   ![](https://i.imgur.com/7MEjMb1.png)

   -[]  Actors: account, cron, exported, init, market, miner, multisig, paych, power, reward, system, verifreg (https://github.com/filecoin-project/specs-actors)
   -[]  A pure API for building on Filecoin. no opinions for how you do that.
   -[]  Offer the user a PowerGate client to connect to the service API at default address at /ip4/0.0.0.0/tcp/5002 and hardcoded in the code block. Once the client is created, `client.FFS.Create()` does the job of creating an FFS instance and returning the `ffsID` and the `ffsToken`.
   -[]  Push config corresponding to CID for persistence of data on Filecoin (cold upload)
   -[]  We could host an entire web3 application on FileCoin, the binaries, the artifacts and assets. When it is run in the user local machine and there is either no backend or just some business logic modeled in a smart contract. Or wecan just use the API from a cetralized service but most of the application and the static assets can be distributed around with Filecoin.
   -[]  Finally, they let you synchronize that with remote peers (i.e. for persisting on always-on IPFS nodes like the Hub)
   -[]  Folder in, Folder out. Changes to folder in, updated folder out. With encryption and IPFS network etc all handled between.Powergate:
   -[]   Hub resources: Key based access to give a user the ability to push to remote nodes; ones that persist on IPFS and with a hub store on Filecoin For Buckets, an adminstrator level encrypted bucket sharing and synchronization schema will be used.
   -[]  Additionally, they have helpful systems for doing that with encryption (and password based encryption).
   
## Buckets
   -[]  Buckets provide a set of Powergate APIs over a hosted service
   -[]  Some of PowerGate’s APIs are exposed for buckets which can be moved to deals in Filecoin with singular commands.
   -[]  Fleek on top of Textile Threads and Buckets on top of IPFS
   -[]  Fully Private file upload via encrypted textile buckets.
   
   ![](https://i.imgur.com/LgGPRlW.png)

   
## Ring of Local Nodes
   -[]  With experimental local syndicate rings using content-specific nodes using IPFS with a Powergate
   -[]  Hosted PowerGate service like local content focused rings
   -[]  User Interface
   -[]  We have created a few very simple databases. Databases that are easy to understand.
   -[]  3 columns each, and index number a source name and the ipfs hash of the content.
   -[]  Virtual tours to digitally visit CryptoVoxel galleries where players view and purchase NFTs. Visiting helps with pinning to ensure longevity.
   -[]  Easily deployable simple NodeJS bootstrapped app wired with Web3 IPFS and Ethereum, akin to the IPFS-js light, with minimal overhead/dependencies. (https://github.com/textileio/js-ipfs-lite)
   -[]  use the DApp without downloading any external wallets or buying any crypto currency from an exchange. This is possible using the concept of meta transactions where user is able to do a transaction on blockchain with zero balance account and any third party can pay for the transaction fees for the user. CHI token, Swag0x onboarding, Web3vm bootstrap
   -[]  Virtual Artist Spaces -- make a hangout spot in cryptovoxels for artists to hang out create and mint art for in-game galleries and art shows
   -[]  IPFS “pin me” widget that any site to link to an IPFS companion in browser to help host a site on IPFS, IPNS and pub-sub for keeping sites updated.
   -[]  Pull any Smart Contracts from OpenLaw and WorldLaw (Smart Contract and ABI stored in Buckets with underlying content)
   -[]  Escrow Agreement (DisputableBuyerSellerAgreement-Factory)
   -[]  Escrow Agreement (DisputableBuyerSellerAgreement-Created by factory) with version control for updating progress.
   -[]  Scripting in CV to run IPFS and Web3 transactions to IPFS and Ethereum blockchain
   -[]  Encrypted Personal photo gallery - google photos but on textile + encrypted
   -[]  Native Meta Transactions Building your first meta transaction enabled DApp
   -[]  A database superimposed in a CryptoVoxel parcel as a live animation and video event.
   -[]  plug and play APIs and SDK reduces friction between your application and your users
   -[]  Use ipfs-unixfs-importer (https://github.com/ipfs/js-ipfs-unixfs/tree/master/packages/ipfs-unixfs-importer)
   -[]  Smart contracts on ethereum that call content on Filecoin (Like OpenSea and NFTs)
   -[]  Mini-Applications that pass content through ipfs hot (Web3vm)
   -[]  Convert any Textile Thread address into a webhook
   -[]  DEMO HERE - PRESENTAION CORE
   -[]  Metaverse Cryptovoxels
   -[]  video / picture sharing.
   -[]  Smart Contract Data
   
## OPTION ONE - IDENTITY
   -[]  Integration with keybase for allowing storing the folder which are publicly available for the user on FileCoin network. 
      ![](https://i.imgur.com/jpCb44t.png)
      
   -[]  Keybase-like top level separation of files: private & public. Use CID for all, but do NOT broadcast or store private files/folders in your local IPFS node.
   -[]  Use Keybase extension to local IPFS client that will automatically copy the public files/folders to your node. (see StakeOnMe)
   -[]  Permanent identity record: Have a set of encrypted buckets with signed identity documents (passports, ID, etc)
   -[]  IPFS - Public Key Infrastructure (PKI) Certificate Authority Decentral (CAD)
### Domain Names
   -[]  ENS templates/uploaders also persist websites with Filecoin (ex using same Ethereum wallet?)
   -[]  Query the web3 address and return ENS characteristics in CV
   
   


![](https://i.imgur.com/RWwWDZM.png)

   ![](https://i.imgur.com/CcoZRZH.png)

   
## OPTION TWO - NON-FUNGIBLE TOKENS IN CRYPTOVOXELS
   -[]  Straight NFTs vs MaxNFTs
   -[]  Build `transloadit` for personal photo collections -- purely API based backend for resampling, sorting, storing. Using ipfs, no locking, open formats. Then invite developers to build any kind of gallery/user interfaces they want on top.
   -[]  Badges for achievements (Non-Transferable) like Skill Levels stored on IPFS and managed via smart contracts. See Swag0x and WorldLaw parcels. (https://www.cryptovoxels.com/parcels/1311 and https://www.cryptovoxels.com/parcels/1378)
   
   ![](https://i.imgur.com/mqpzAkY.png)

   -[]  Music sharing service: for artists before they release music so they control who can access the content and prevent it from getting leaked. Producing edits, tweaks and additions via permission. Machi-X
   -[]  An artist could upload a piece of content through textile and then through an ERC NFT token structure rewards for buyers incentivizing first purchase and collecting InfiNFT
   -[]  Limited edition records and brands -- Brand Devlopement tracking assests by maxNFT - MetaFactory
   -[]  Gated art gallery with an pay an entrance fee and distribute it to all the artists
   -[]  MaxNFT for defining an artists usage and royalty rights
   -[]  NFT for art on IPFS + Textile + Filecoin.
   -[]  NFT to provide ownership of a file.
   -[]  Patient controlled medical record platform
   -[]  Business Files and Records
   -[]  Audio, Video and other Digital File Storage
   -[]  Digital Evidence for Courts
   -[]  Personal Files
   -[]  Last Wills
   
   ![](https://i.imgur.com/9P8IImU.png)

   
## OPTION THREE - PERMISSIONED TOKENS
   -[]  Private curated art gallery tours in CryptoVoxels where all assests are derved from CID’s in buckets negotiated through PowerGate and FileCoin (Junkyard Tour in CryptoVoxels)
   
   ![](https://i.imgur.com/jyaYJnV.png)

   -[]  Limited edition NFT tokens with encrypted data that is unlocked by IPFS files and content is delived thorugh automated functions on smart-contract in Ethereum, Once the services are rendered the user keepsthe NFT as a souvenir.
   -[]  Service to manage continuous payments using multiple token swaps and money streaming for a group of people in one tap. It ensures on-chain payment approval from trusted authorities and data privacy via end to end encryption.
   -[]  Private p2p video chat and messaging using libp2p protocols; something simular to a token-based or key-based Sensitive Compartmented Information Facility SCIF
   
   ![](https://i.imgur.com/0zsPwkj.png)

   
## OPTION FOUR - ALL ABOUT ENCRYPTED BUCKETS
   -[]  Textile PowerGate - Store it on PowerGate.
   
   ![](https://i.imgur.com/xQv5l6Q.png)

   -[]  Image Search - Indexing Keypoints based partial image hashes to find partial image content (composite images)
   -[]  Proxy Re-Encryption. Where the storage provider only holds encrypted data but can re-encrypt data for third-parties by proxy for another third party without decrypting.
   -[]  Zero-knowledge Notary: Store encrypted data on nodes that can be used as permanent proofs for notarized files.
   -[]  Upload and retrieve personal encrypted data/files such as various account credentials, medical record, tax forms, financial statements, photos, videos etc. through Web3 Account and using a trasnaction signing tool like MetaMask. Ability to grant managed access to others, and track data use.
   
## OPTION FIVE - RING OF LOCAL NODES EXPOSING NODE VIA LIBP2P
   -[]  Libp2p network connectivity mapping general visualization of libp2p connections for nodes that voluntarily report this data -- could be useful to introspect ipfs, filecoin, eth2, polkadot, keep, 0x, etc.
   -[]  Allow a storage miner to “follow” a collaborative cluster. Syndicates use FileCoin wallet associated with a collaborative cluster to pay the storage miner.
   
   
   -[]  Network alert bot. Tells you if any easily configured attribute of the IPFS Public DHT or Filecoin Blockchain trigger (ex, response time on X was >5 sec, X nullblocks seen in 5 mins, etc)
   
### Collaborative Clusters
   -[]  Content Discovery
   -[]  Local Area Networks
   -[]  Private Networks
   -[]  Gated Content Management by Subject Type and Jurisdiction (Civil Prodecures)
   -[]  Incentivized DHT -- pay for DHT PUTs and/or GETs
   -[]  Logging the deals to keep the miners honest or run your own local ring.
   -[]  Network Visualization & Maps
   -[]  Analytics & Metrics
   -[]  Visualize a set of available peers within the network. Allow for additional, user interactions to take place.
   -[]  DHT access visualization. Visualize how dht queries work and how they access nodes in the network
   -[]  Subscriptions and Payments by Relay
   
   
# SOME TEAM ACTIONS TO GET STARTED

![](https://i.imgur.com/toBNOl3.png)


## Syndicate of a Local Node Ring
   -[]  Connect ring-nodes to cold network strapped by Filecoin
   -[]  One gateway hot node exposed to the WAN using libp2p
   -[]  A proxy (lead node) negotiates the cold storage deal
   -[]  the local ring picks a lead node as a proxy
   -[]  Assign .eth names to ring-nodes
   -[]  Use content routing in libp2p
   -[]  Storage and Retrieval schemas for content indexing
   
## IPFS to Ethereum Bridging with Gas Tokens
   -[]  Ethereum transactions paid by with CHI Gas tokens
   -[]  Since minting NFTs is relatively expensive, combined with a CHI gas token to can swap them for other tokens on the 1inch exchange which provides discounted gas transactions. Use CHI to test. (worldlawAccount 454.00 CHI, regencyAccount 505.00 CHI)
   -[]  Prices negotiated by the local ring
   
## Other Good Starting Points
   -[]  Use the JSON files to help with parsing the valuable information from IPFS to parse the Ethereum blockchain to deliver the content.
   -[]  Run javascript to parse all eth erc20 and erc721 assets via meta-transactions
   -[]  Compose a custom CID hash by pubsub topic
   -[]  Pull all json files from 721 URI
   -[]  Token or NFT badge muti-drop by a gatekeeper or proxy account (Airdrop.eth) using a treasury relay account
   -[]  Provided Airtable database for running demos and tests
   -[]  Devlop a solution and protocol using NodeRed.
   -[]  Deployments on Kovan, Rinkeby and Ethereum public chains.
   -[]  Run Tests on QUICKBEAMS Web3 accounts (Qfinney.eth, Ufinney.eth … Mfinney.eth, Sfinney.eth)
   
` Add data to IPFS cache and get CID (hot upload)  async function hotUpload(blob) {     var audioBuffer = await blob.arrayBuffer();     var input = new Uint8Array(audioBuffer);     const { cid } = await pow.ffs.addToHot(input);     return cid; }  The blob already contains the recorded audio data that I convert to an Uint8Array to pass as an input parameter to pow.ffs.addToHot().  Push config corresponding to CID for persistence of data on Filecoin (cold upload)  async function coldUpload(cid) {     const { jobId } = await pow.ffs.pushConfig(cid);     return jobId; }  This default config that we push corresponding to the cid here determines how we wish to persist the content on Filecoin.`

` async function getTrackContent(cid) {     const audioBytes = await pow.ffs.get(cid);     const audioBuffer = audioBytes.buffer;     var blobOpts = { 'type' : 'audio/wav; codecs=0' };     if (MediaRecorder.isTypeSupported("audio/wav;codecs=MS_PCM")) {         blobOpts = { 'type' : 'audio/wav; codecs=MS_PCM' };     }     const blob = new Blob([audioBuffer], blobOpts);     const url = URL.createObjectURL(blob);     return url; }  pow.ffs.get() tries to first retrieve the content corresponding to the CID from IPFS cache and if unavailable, gets the content from Filecoin after a confirgurable timeout.`

` // watch the FFS job status to see the storage process progressing const cancel = pow.ffs.watchJobs((job) => {   if (job.status === ffs.JobStatus.CANCELED) {     console.log("job canceled")   } else if (job.status === ffs.JobStatus.FAILED) {     console.log("job failed")   } else if (job.status === ffs.JobStatus.SUCCESS) {     console.log("job success!")   } }, jobId)`

    
## Notes

### Action Items

1. a
2. b
3. c
4. d
5. e
6. f
7. g
8. h
9. i










==============================
TEMPLATE BELOW DO NOT REMOVE


### This Week  
- abs
    - abs
- abs
- abs
- abs
- abs




| Column 1 | Column 2 | Column 3 |
| -------- | -------- | -------- |
| Text     | Text     | Text     |




## Agenda:

- First Section - 20 min 
    - [ ]  item x
    - [ ]  item x
    - [ ]  item x

- Second Section 30 min
    - [ ]  item x
    - [ ]  item x
        - [ ]  item x
    - [ ]  item x
    - [ ]  item x
    - [ ]  item 5
    - [ ]  item 6
        - [ ]  Sub 6a
        - [ ]  Sub 6b
            - [ ] abs
        - [ ]  Sub 6c
    - [ ]  item 7
        - [ ] abs
    - [ ]  item 8


Syntax
# Header


**Bold font**
*Italics font*
~~Strikethrough~~

19^th^
H~2~O
++Inserted text++
==Marked text==
Link 	[link text](https:// "title")
Image 	[image alt](https:// "title")

{%youtube youtube_id %}

:smile:

$L^aT_eX$

:::info
This is a alert area.
:::

    
`Code`

`Code`

```javascript
var i = 0;
```
