# rWAllet - Project FutureWALLET -

Wallet Connect Example using Reach

To use TestNet:
`export REACH_CONNECTOR_MODE=ALGO-live`
`export ALGO_TOKEN='2f3203f21e738a1de6110eba6984f9d03e5a95d7a577b34616854064cf2c0e7b'`
`export ALGO_SERVER='https://academy-algod.dev.aws.algodev.network'`
`export ALGO_PORT=''`
`export ALGO_INDEXER_SERVER='https://algoindexer.testnet.algoexplorerapi.io'`
`export ALGO_INDEXER_PORT=''`
`export ALGO_INDEXER_TOKEN=''`

**Install prerequisites**

Install [node.js](https://nodejs.org/en/download/)
`npm install`

Install react
`npm install react --save`

Install Reach
`curl https://docs.reach.sh/reach -o reach ; chmod +x reach`
`./reach update`

Change the settings in the Algo Pera Wallet to TestNet

Settings | Developer Settings | Node Settings | TestNet

To Run:
`make react` to try it out.

More ideas for this repo to consider:

Add some meta information, like the name of the event, a URL for it, plus a logo, and maybe a color scheme.

Expose the meta information in a View.

Make the main site immediately go to the "Launch" mode and after it is done, generate a QR code for https://rsvp.reach.sh/?ctc=THE_CONTRACT_INFO.

Make it so if you go to one of the ?ctc addresses, then it will see if you're the creator and immediately show the check-in UI and if not, then it will show the RSVP UI.

In the check-in UI, make it so the default is to scan the address with a QR code.

Allow the RSVP'er to decide how much they want to stake, with a minimum specified by the creator.

Have the RSVP'er pay a small amount to the Creator (because the Creator needs to pay fees to actually do the Check-in) --- Right now on ALGO, that would be 0.002 ALGOs.

In the RSVP UI, show information about how many people have RSVP'd and how much they've staked.

