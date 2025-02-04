# Mint-An-NFT

### Overview
Mint-an-NFT is a free tool provided by @XCHcentral (https://twitter.com/xchcentral) to the chia community to help mint NFTs.
The tool was developed for @ChiChiverse_NFT(https://twitter.com/ChiChiverse_NFT). The tool requires users to have
an 1.4.0+ Chia Client on their machine in order to execute the CLI command generated by the Mint-an-NFT tool.

#### IMPORTANT !!
This tool is in ALPHA. There is a lot of room for improvement such as error handling. Use at your own risk.

This tool SHOULD NOT be used by non-technical users who do not feel 
comfortable inspecting the command generated and understanding what it does.

You should never execute commands against your Chia CLI client without understanding what they do!!

### Requirements
* An up-to-date chrome, safari, or firefox is required. The tool uses the browsers built in crypto library to generate the sha-256 hashes of images and metadata. This has been tested on chrome 103.0.5060

* nft.storage API KEY - Mint an NFT uses nft.storage api to upload your images to IPFS. 
You'll want to register for an account at nft.storage and get an api (https://nft.storage/docs/#get-an-api-token)

### Running the minting tool
* Update the constants in the top of file chichi.js
* Save changes to chichi.js before continuing
* Open chichi-ui.html in your up-to-date modern browser
* Follow the steps in the tool to 
  * Upload image to ipfs via nft.storage
  * Generate the JSON for the NFT 
  * Upload JSON metadata to nft.storage
  * Generate CLI command
* Copy CLI command to where your chia client is running to execute MINT command

### Reporting issues
XCHcentral looks forward to community input on ways to improve the tool - however development may be slow. Feel free to open up issues here in github and we'll do our best to review.

### License
GNU General GPL v3.0

### Donations
Like the tool? Feel free to donate XCH or NFTs to: xch1dwm59nranz0khzfzmv0j9g4tpwe4fx7ven0ptr9hufs2c0kgesxq8r7mws