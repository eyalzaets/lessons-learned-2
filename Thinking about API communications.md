Before this class my understanding of APIs was very general. I knew that that APIs allowed two different pieces of software to talk to each other, but that was more or less the extant of my knowledge.

I found it very helpful to learn more about how APIs work and how one might build one. In particular, I learned a lot from the process of thinking about the different communications that would have to take place in a given API. Breaking down the different communications that would need ot take place for an API to work allowed me to gain a deeper understanding of the complexity of APIs and how to direct an engineering team in specifying the API. 

For example, if you’re working for a startup that is planning to provide same day shipping for a number of different online retailers and you want to be able to display a “same day shipping” price in the checkout process for each retailer, you would need to build an API that would require at least four main communcations:

1. Communcation from us to the retailers about products in our inventory, including the SKU, quantity on hand in each warehouse, and the different zip codes that can be serviced from those warehouses within the same day based on what time the product is ordered. 
2. When a customer opts for same-day shipping, the retailer would have to send their order information to us, including the product SKUs, quantities, and the customer’s address. 
3. New inventory information would have to be sent back to the retailer along with confirmation that the order was fulfilled or any problems fulfilling the delivery. 
4. We would send retailers analytics that may help with their business. For instance, based on ordering patterns and in-stock data, we can send them analytics that will help improve inventory allocation across our network of warehouses. 

Thinking about how to specify APIs also gave me greater insight into how companies decide whether to allow an open API to all developers for free (open API) or restrict access to developers that pay for access (closed API). I found this article on LinkedIn's recent decision to restrict its API use particularly interesting: http://techcrunch.com/2015/02/12/linkedin-battens-down-the-hatches-on-api-use-limiting-full-access-to-partners/#iVKfmk:u8d

![alt text](http://library.csu.edu/csit/nf/intro/images/computers.gif)

