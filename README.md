Creating of NFT
This is a Javasript program that used different functions and data types. 

This program allows users to create and manage a collection of Non-Fungible Tokens (NFTs). 
Each NFT has metadata attributes such as name, eye color, shirt type, and bling. 
The program includes functions to mint new NFTs, list all NFTs, and get the total number of minted NFTs.

To run this program, you can use online Javascript IDE. To get started, go to https://onecompiler.com/javascript
https://onecompiler.com/javascript

Executing program
Once you entered the site, you can simply just copy and paste the following code into the compiler

// create a variable to hold your NFT's
const NFTs = []

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (_name, _eyeColor, _shirtType, _bling) {
   const NFT = {
       "name": _name,
       "eyeColor": _eyeColor,
       "shirtType": _shirtType,
       "bling": _bling
   }
   NFTs.push(NFT);
   console.log("Minted:" + _name);
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {
   for(let i = 0; i < NFTs.length; i++) {
     console.log(NFTs[i]);
   }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
   console.log(NFTs.length);
 }
// call your functions below this line
mintNFT("Dave", "Black", "Shirt", "Diamond Chain");
listNFTs();
getTotalSupply();

after you input the code you can just simply click the "run" button on the upper right and the program will start running. 

John Dave A. Rizada
422002188@ntc.edu.ph
