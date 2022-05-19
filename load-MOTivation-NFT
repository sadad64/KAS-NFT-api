const CaverExtKAS = require('caver-js-ext-kas')

const accessKeyId = "{accessKey ID}"
const secretAccessKey = "{Secret Access Key}"
const chainId = 8217 // Klaytn test chain

// Header certification

async function loadInfo() {

    const caver = new CaverExtKAS(chainId, accessKeyId, secretAccessKey)
    // Kaikas caver initialize

    const contractAddress = '0x9faccd9f9661dddec3971c1ee146516127c34fc1' // NFT contract address
    const tokenId = '1470431112' // specific NFT token ID in NFT contract 
    const result = await caver.kas.tokenHistory.getNFT(contractAddress, tokenId) // get NFT history

    console.log(result);
}

loadInfo(); // load async function
