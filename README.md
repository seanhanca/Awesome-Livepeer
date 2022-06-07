
# Awesome Livepeer
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


Welcome to the central learning resource for everything Livepeer: A curated list of awesome Livepeer resources, libraries, tools and more.

Please check the [contribution guidelines](https://github.com/seanhanca/eLivepeer/blob/main/Contributing.md) for information on formatting and writing pull requests.

# Table of Contents
- [Context](#context)
  - [Web3 Basics](#web3-basics)
  - [Streaming Basics](#streaming-basics)
  - [dApps Basics](#dapps)
  - [ETH Basics](#eth-basics)

- [Livepeer Basics](#livepeer-basics)
  - [White Papers](#white-papers) 
  
- [Everything Ops](#everything-ops)
  - [Livepeer Github Repos](#livepeer-github-repos) 
  - [Livepeer CI/CD Pipelines](#livepeer-cicd) 
  
- [Latest Trends](#latest-trends) 

- [More Rerources ...](#resources)


# Context

## Web3 Basics
-  [Top Web3 Architecture Layer Explained](https://itnext.io/top-3-web-3-0-architecture-layers-explained-frontend-backend-and-data-e10200f7fc76)
-  [A Developer’s Guide to Web 3 Stack](https://alchemy.com/blog/web3-stack)
-  [The Architecture of Web 3 Applications](https://www.preethikasireddy.com/post/the-architecture-of-a-web-3-0-application)
-  [Decentralization for Web3 Builders: Principles, Models, How](https://future.com/web3-decentralization-models-framework-principles-how-to/)
-  [Web 3 Security: Attack types and Lessons Learned](https://a16z.com/2022/04/23/web3-security-crypto-hack-attack-lessons/)
-  [Awesome IPFS](https://github.com/ipfs/awesome-ipfs#readme)
-  [Awesome Web3](https://github.com/JoinColony/awesome-web3)

## Streaming Basics
-  [Mist Streaming Articles](https://news.mistserver.org/news/65/Fantastic+protocols+and+where+to+stream+them)
-  [Awesome Video](https://awesome.video/)
-  [Internet Video Streaming part 1 ](https://medium.com/@eyevinntechnology/internet-video-streaming-abr-part-1-b10964849e19)
-  [Internet Video Streaming part 2](https://medium.com/@eyevinntechnology/internet-video-streaming-abr-part-2-dbce136b0d7c)
-  [Internet Video Streaming part 3 ](https://medium.com/@eyevinntechnology/internet-video-streaming-abr-part-3-45ff4bb3d436)
-  [Chessboard for Beginners Video-encoding Compression and Resolutions](https://medium.com/@eyevinntechnology/chessboard-for-beginners-video-encoding-compression-and-resolutions-bcefe04fa639)
-  [Quality of Experience in Streaming](https://medium.com/@eyevinntechnology/quality-of-experience-in-streaming-5c25355a4111)
-  [Part-1 Back to Basics GOPs  Explained/](https://aws.amazon.com/blogs/media/part-1-back-to-basics-gops-explained/)
-  [Streamline](https://github.com/streamlinevideo/streamline)
## dApps Basics
- [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
- [Awesome Blockchain](https://github.com/openblockchains/awesome-blockchains)
- [Full Solidity Course Python Edition](https://github.com/smartcontractkit/full-blockchain-solidity-course-py)
## ETH Basics
- [Awesome ETH](https://github.com/bekatom/awesome-ethereum)
- [Awesome Decentralized P2P](https://github.com/decentropy/awesome-decentralized)

# Livepeer Basics
- [10 min Livepeer Primer](https://livepeer.org/primer)
- [First Livepeer Stream in Five Minutes](https://livepeer.com/blog/first-livepeer-stream-in-five-minutes)
- [Livepeer Always-on Transcoding Network](https://livepeer.com/blog/livepeer-always-on-transcoding-network)
- [Live Peer Network Phases](https://medium.com/livepeer-blog/livepeer-network-phases-b196ab42264b)
- [Livepeer Roadmap 2021 and beyond](https://medium.com/livepeer-blog/the-livepeer-roadmap-2021-and-beyond-5281776e9b3d)
- [The Livepeer Governance Founders Statement](https://medium.com/livepeer-blog/the-livepeer-governance-founders-statement-d4f3a85f787b)
- [The Best Resources for Token-holders](https://medium.com/livepeer-blog/the-best-resources-for-token-holders-2e484c8d9736)
- [The video-miner a path to scaling video transcoding](https://medium.com/livepeer-blog/the-video-miner-a-path-to-scaling-video-transcoding-a3487d232a1)
- [The Streamflow Proposal Scaling Livepeer](https://medium.com/livepeer-blog/the-streamflow-proposal-scaling-livepeer-72179b20bfdd)

## White Papers
-  [Livepeer White paper](https://github.com/livepeer/wiki/blob/master/WHITEPAPER.md)
-  [Protocol Research A](https://forum.livepeer.org/c/governance/17)
-  [Protocol Research B](https://forum.livepeer.org/c/research/15)

# Everything Ops
## Livepeer Github Repos
- **protocol (confluence)**
    - [https://github.com/livepeer/protocol/tree/confluence](https://github.com/livepeer/protocol/tree/confluence)
    - The Confluence implementation of the protocol contracts that is meant to be deployed on Arbitrum One
- **protocol (streamflow)**
    - https://github.com/livepeer/protocol
    - The Streamflow implementation of the protocol contracts that is currently deployed on Ethereum
- **arbitrum-lpt-bridge**
    - https://github.com/livepeer/arbitrum-lpt-bridge
    - Contracts that bridge Ethereum and Arbitrum One
    - Implements L1 <> L2 LPT transfers
    - Implements L1 → L2 stake migration
    - Implements L1 → L2 broadcaster funds migration
    - Implements L1 → L2 LPT total supply caching
- **go-livepeer**
    - https://github.com/livepeer/go-livepeer
    - [Developer docs](https://github.com/livepeer/go-livepeer/tree/master/doc)
    - The Go implementation of the Livepeer protocol and the node software the users in the network run in order participate as broadcasters, orchestrators or transcoders
    - Implements networking between broadcasters, orchestrators and transcoders
    - Implements the video pipeline that is used by orchestrators and transcoders to receive, process (decode, encode, apply filters, etc.) and return video to the rest of the network
    - Implements automated on-chain transaction workflows to interact with protocol contracts i.e. reward calls, payment redemption, etc.
- **LPMS**
    - https://github.com/livepeer/lpms
    - [Docs on quirks](https://github.com/livepeer/lpms/blob/master/doc/quirks.md)
    - The Go media processing library that is used in go-livepeer and also contains the video transcoding pipeline logic
    - Uses C ffmpeg/libav libraries under the hood that is called from Go via cgo
    - Depends on the Livepeer ffmpeg fork
- **ffmpeg**
    - https://github.com/livepeer/FFmpeg
    - The Livepeer ffmpeg fork that contains some custom features used in LPMS
- **docs**
    - https://github.com/livepeer/docs
    - User facing docs that can be found at [https://docs.livepeer.org/](https://docs.livepeer.org/)

# Latest Trends

# More Resources
