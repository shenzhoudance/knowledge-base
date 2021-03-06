{
"title"       : "Adding Custom Ethereum (ERC-20) Tokens",
"sort"        : "01",
"category"    : "Tokens",
"description" : "Tokens",
"date_published" : "2017-07-05T08:00:00+08:00",
"date_modified"  : "2017-11-11T09:07:00+08:00"
}

---%

  If you have a token that you would like to access on our interface, but don’t see it on our default list, you can add the token locally in your own interface as a custom token. This can be achieved relatively easy from the following steps.  

  *Disclaimer: None of your ETH or tokens are stored on our site. All of your funds are on the blockchain itself, so removing custom tokens and seeing ‘0’ balances does not mean your tokens are lost! We are only an interface to interact with the blockchain.*  

  __Step 1:__ Access your wallet on our site. This can be done under the “View Wallet Info” tab on the main page of our interface. Choose whichever method of access you usually choose.

  __Step 2:__ To the right of the screen, you will see a ‘Token Balances’ area with two buttons, “Show All Tokens” and “Add Custom Token”.

  __Step 3:__ Click “Show All Tokens” and press Ctrl + F (or Command + F if you’re using a Mac). Search for the token you are trying to see, just in case it’s already a default! We are constantly updating our default token list for your convenience.

  __Step 4:__ Now that you have determined your token is not in our default list, head over to etherscan.io. Plug in your Public Address into the search function on etherscan, and find the page that shows your balance and transaction history. If you have tokens, you will see a drop-down menu of token balances to the right of the page.

  __Step 5:__ Click which of these tokens you are trying to add, and you will be taken to a page that lists the Contract Address and Decimal count for the token you are viewing. This is the information required to add any ERC-20 token as a custom token on our interface. A contract address looks the same as a public address.

  __Step 6:__ With your wallet unlocked on our site, click the “Add Custom Token” button. Fill in the contract address and decimal count fields, then input the abbreviation for your token as the ‘Symbol’. For example, OmiseGO -> OMG.

  __Step 7:__ Save the custom token, and you’re all set! Your token should appear in the default list, with a remove button “(-)”, and the balance should match what shows on etherscan.io.

  Here is a sample of the MAD token, for reference to what this information will look like:
  ```
    Symbol: MAD
    Contract Address: 0x5B09A0371C1DA44A8E24D36Bf5DEb1141a84d875
    Decimal: 18

  ```  

### Common Issues:
  * Balance loading as 0? Check etherscan.io at your public address. Is the token balance there? If so, try accessing another network/node in the upper right hand corner of our interface. It defaults to “Network ETH myetherapi.io”, so try any other ETH network! I.e. ‘giveth.io’, ‘infura.io’, or ‘etherscan.io’.

  * Receiving any errors? Please make sure that this is an ERC-20 token that appears on etherscan.io, that you don’t have any spaces before or after the address, and that all information is entered accurately. If you are still having issues, try another network/node as mentioned in the previous bullet.

  * Need a checksummed contract address? In Step 5, click the contract address of the token. This will take you to another form of the address, which includes both upper and lower-case letters.

  * Tokens disappearing everytime you close the browser? This is the cause of a local cache cleaning software, such as CCleaner. Please make sure that your browser isn’t being constantly cleared of information, as all custom token information is stored locally.

If you are still experiencing issues, have further questions, or want us to find a token’s address and decimal count for you, please contact us at [support@myetherwallet.com](mailto:support@myetherwallet.com) and we would be happy to assist you! *-Stephen #MEWForce*


### Related Reading
- [Adding a New Token & Sending Custom Tokens](https://myetherwallet.github.io/knowledge-base/send/adding-new-token-and-sending-custom-tokens.html)
