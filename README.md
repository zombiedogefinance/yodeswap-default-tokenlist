---
description: 'Build on Yodeswap and need help? let us know.'
---

## ✨ Building on Yodeswap and DogeChain

## **Yodeswap Mainnet Contracts:**

`Mainnet Deployed @ https://yodeswap.dog`

**Router Address**: `0x72d85Ab47fBfc5E7E04a8bcfCa1601D8f8cE1a50`

**Factory Address**: `0xAaA04462e35f3e40D798331657cA015169e005d7`

**Multicall Address**: `0xBBa16192B6F91765ABDFb795934835113D6d552B`

**WWDOGE Address**: `0xB7ddC6414bf4F5515b52D8BdD69973Ae205ff101`

## How to get your token LOGO on Yodeswap:

### 1. Image for the Token Logo <a id="1-image-for-the-token-logo"></a>

> * **File Extension**: `png` . Uppercase `PNG` is considered invalid
> * **File Name**：`logo.png`
> * **Size**: `256px by 256px`
> * **Background**: Transparent is a must

### 2. Token Information File <a id="2-token-information-file"></a>

> * Fork the repository and add the token information (example below) to yodeswap.tokenlist.json
> * Create a folder under assets/{blockchainName}/{tokenAddress}
> * Add the token icon (logo.png) under the folder created in the previous step
> * Add the token information in the yodeswap.tokenlist.json file, in the format shown below

The sample below shows what information has to be included on the `yodeswap.tokenlist.json` file.  
Please make sure that the details are accurate and follows the formatting.  
The contract address should follow the checksum address format \(see next requirement\).

```
{
       "chainId":2000,
       "address":"0x6FC4563460d5f45932C473334d5c1C5B4aEA0E01",
       "name":"Yodedex Token",
       "symbol":"YODE",
       "decimals":18,
       "logoURI":"https://raw.githubusercontent.com/yodedex/yodeswap-default-tokenlist/main/assets/dogechain/0x6FC4563460d5f45932C473334d5c1C5B4aEA0E01/logo.png"

},

```

## How to get your LOGO Approved

Fork and Submit @ [https://github.com/yodedex/yodeswap-default-tokenlist](https://github.com/yodedex/yodeswap-default-tokenlist) 

The Pull request will be screened before it gets added to the repository. In order to get approved, your submission must meet the following requirements.

* **Project has a website.**
* **Has a social media presence.**
* **Project must have some trading volume (ie. > $ 20k). This is subject to per project review**
* **Verified Contract on DogeChain Explorer.**
* **Detailed Token Information.**
