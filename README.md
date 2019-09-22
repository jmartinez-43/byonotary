# BYONotary
An application that allows you to notarize a digital file without a 3rd party. In other words, people can use this app to prove that they were in possession of a digital file at a certain point in time. 

## Disclaimer
I created this application in order to practice programming. It is not ready for use, nor should it be considered secure or finished in its current form. 

## How BYONotary leverages the blockchain
This app utilizes the blockchain in order to store hashes of digital files in the BYONotary smart contract. A mapping data structure is used to keep track of hashes that were stored by a specific address. 

I also included a function in the BYONotary smart contract that allows users to prove to a 3rd party that they were in possession of a specific file at a specific point in time. 

## Privacy
The blockchain is fascinating because it can authenticate large amounts of data that lives offchain with only a hash that is stored onchain. This allows users to notarize data while hiding what that data actually is. 

## UX
My goal is to keep this app as simple as possible in order to encourage use. 
