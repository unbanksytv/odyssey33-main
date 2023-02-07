<h3 align="center">Odyssey MVP V2 [BETA]</h3>
  <p align="center">
An open source NFT marketplace built on Reservoir, Thirdweb SDK and Manifold Creator Contracts.

<h3>🄶🄾🄾🄳 🅅🄸🄱🄴🅂 🄾🄷🄼🄻🅈</h3>

<!-- ABOUT THE PROJECT -->

## About The Project

Reservoir Market v2 is an open source marketplace built with Reservoir APIs that enables access to instant liquidity aggregated from major marketplace. Odyssey is a community-driven marketplace and aggregator in one. It lets you analyze and purchase many NFTs at once from multiple marketplaces. A common use case that requires buying multiple NFTs in a single transaction is floor-sweeping, which is slang for purchasing numerous of the lowest-priced NFTs from a specific collection. The app compiles NFT listings from popular markets, as well as allows users to offer their assets natively on Odyssey. Listing options include floor price, trait floor price, and in the same flow also list on OS, LR, etc, ...

Collections are shown in the order of their one-day trading volume by default, and essential data elements such as floor price, number of owners, and other price and volume indicators are displayed at a glance. It also displays the scarcity of certain NFTs and allows users to view the floor price for specific attributes and make offers on a collection level, or make an offer on very specific traits, and get a clear indication of the current floor prices for these traits. 

The portfolio page allows users to see all of the Ethereum-based NFTs in their wallet, and it aims to integrate NFTs into other networks in the future.

## Features:

Instant buy with aggregated liquidity
Referrer fees on top of aggregated orders
Listing on all major marketplaces
Real-time floor prices per trait
Top bid changes, daily volume, and sales data
Real-time and historical activity (more thoon)
Listings, bids, transfers, etc, .. across marketplaces
Selling to the highest bid directly from your wallet
Add missing royalty fees on top of aggregated orders
Automatic handling of transaction approval steps
Balance checks and error handling
Suspicious token warnings

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started (Self-Hosted)

### Prerequisites

1. Install [Node.js and NPM](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
2. Install [Yarn](https://classic.yarnpkg.com/en/docs/install)
3. Request free [Reservoir API key](https://reservoir.tools/request-api-key)

### Built With

- [ReservoirKit](https://docs.reservoir.tools/docs/reservoir-kit)
- [Reservoir Protocol and API](https://reservoirprotocol.github.io/)
- [Next.js](https://nextjs.org/)
- [React.js](https://reactjs.org/)
- [Ethers.io](https://ethers.io/)
- [WAGMI](https://wagmi.sh/)
- [Stitches](https://stitches.dev/docs/variants)

### Installation

Fork this repo and follow these instructions to install dependancies.

With yarn:

```bash
$ yarn install
```

With NPM:

```bash
$ npm install
```

### Configuration

Reservoir Market v2 is lightly configurable with the configurations below. You can either add these to a `.env.production` and `.env.development` or add env variables to a deployment platform like [vercel](https://vercel.com/).

**Environment Variables**
| Environment Variable | Required | Description | Example |
|--------------------------------|----------|-------------------------------------------------------------------------------------|---------------------|
| NEXT_PUBLIC_HOST_URL | `true` | The domain that the deployed project is hosted on. | http://localhost:3000 |
| ETH_RESERVOIR_API_KEY | `false` | Ethereum Reservoir API key provided by the Reservoir Protocol. [Get your own API key](https://reservoir.tools/request-api-key). | 123e4567-e89b-12d3-a456-426614174000 |
| GOERLI_RESERVOIR_API_KEY | `false` | Goerli Reservoir API key provided by the Reservoir Protocol. [Get your own API key](https://reservoir.tools/request-api-key). | 123e4567-e89b-12d3-a456-426614174000 |
| POLYGON_RESERVOIR_API_KEY | `false` | Polygon Reservoir API key provided by the Reservoir Protocol. [Get your own API key](https://reservoir.tools/request-api-key). | 123e4567-e89b-12d3-a456-426614174000 |
| NEXT_PUBLIC_ALCHEMY_ID | `true` | Alchemy API key required for removing rate limiting restrictions. [Get your own API key here](https://docs.alchemy.com/alchemy/introduction/getting-started#1.create-an-alchemy-key). | 123e4567-e89b-12d3-a456-426614174000 |
| NEXT_PUBLIC_COLLECTION_SET_ID | `false` | Use this to configure a community marketplace. Generate your collection set ID [here](https://docs.reservoir.tools/reference/postcollectionssetsv1). | f566ba09c14f56aedeed3f77e3ae7f5ff28b9177714d3827a87b7a182f8f90ff |
| NEXT_PUBLIC_COMMUNITY | `false` | Use this to configure a community marketplace. Note: Community IDs are only available for certain communities. | artblocks |

### Run the App

Once you have your setup ready, run:

With yarn:

    $ yarn dev

With npm:

    $ npm run dev

### Deploy with Vercel

This is a Next.js app that can be easily deployed using [Vercel](https://vercel.com/). For more information on how to deploy your Github repository with Vercel visit their [docs](https://vercel.com/docs/concepts/projects/overview).

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Twitter: [@reservoir0x](https://twitter.com/reservoir0x)
Discord: [Reservoir](https://discord.gg/j5K9fESNwh)
Project Link: [Reservoir](https://reservoirprotocol.github.io/)

<p align="right">(<a href="#top">back to top</a>)</p>
