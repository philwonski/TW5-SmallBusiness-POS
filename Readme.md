Readme.md 

This is a starter pack for a low-code small business POS (point-of-sale) system. Thanks to the power of [Tiddlywiki](https://tiddlywiki.com), you can style however you'd like, as well as add functionality using Tiddlywiki's Wikitext syntax or using javascript. 

1. This app replaces paper-based Order Forms and also allows you to track orders through the fulfillment process. 
* It works great on a local network using a Raspberry Pi and [pm2](https://medium.com/@andrew.nease.code/set-up-a-self-booting-node-js-eb56ebd05549). 
* You can also easily secure it on a VPS and access it from anywhere using Cloudflare Argo Tunnels. 

2. The app runs on the nodejs version of Tiddlywiki; but to take it for a quick spin, you can just visit the output/index.html file. 

3. The app supports up to **two terminals**, such as a storefront with a cash register/computer up front and a back office computer. 

* All the functionality is the same in the two views. Separating them just allows you to track who is using which terminal and what info is generated there. 
* The cash register home screen can be accessed by visiting myDomainOrIP`/#FrontDesk%2FHome`.
* The cash back office home screen can be accessed by visiting myDomainOrIP`/#BackOffice%2FHome`.

4. The Universal Search bar will search all orders, as well as help you begin an order. 
* Simply enter some info about the order to begin. 
* If the customer has never ordered before, simply click the "Start Order" button to begin.
* If the customer has ordered before, you can click one of their existing orders and, below their contact info, select "New Order with this Account."