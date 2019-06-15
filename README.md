# A Simple Decentralized Bookstore

## Description
A simple Dapp that user can up load books in pdf format and to set the price. Other users can select select the books to buy, pay in Ether and download the book.

## User Interface of the Dapp
On startup of the Dapp, the screen is to display all the books that are available for sale. To keep the front end design simple, it is assume that there are no more than 10 books to be sold in the bookstore. The books available are to be displayed in the order they are upload along with it selling price and a buy button. 

At the bottom of the page there is a place for user to upload a book to the Bookstore. User is to enter the name of the book and the price that he/she wished to sell. When these items are specified, user can hit the **Upload** button and then the **submit** button to put the book in the Bookstore for sale.

In the first phase of this Dapp there is minimal error checking at the user interface. Also, in this phase, user is not able to remove the book from the Bookstore.

## Operations of the Front end 
### Interface with ISPF
Front end is to store the book (in pdf format) in IPFS. 

### Interface with Smart Contracts via Web3
The IPFS hash is to be stored in the smart contract when the book is added to the Bookstore.

## Smart Contracts
1.  booksAvailable()
2.  buyBook()
3.  addBook()
4.  fetchBook()
