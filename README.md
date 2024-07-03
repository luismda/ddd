# DDD

> Case study to identify entities and use cases, using DDD principles. 🔥

## Case

Developer: Hi, thanks for participating in the interview. To start, what are the main features you would like to see in this stock management system?

Domain Expert: We need a solution that allows us to track each product individually, set minimum stock quantities, and receive alerts when we are running out of a certain product. It would also be helpful if we could view sales and stock history to help us make future purchasing decisions.

Developer: Got it. Could you give me an example of how you would like the individual product tracking functionality to work?

Domain Expert: We would like to be able to assign a unique identification number to each product so that we can easily track its movements in our stock. It would also be helpful if we could add extra information like size and color to make tracking even more accurate.

Developer: What about the functionality for setting minimum stock quantities, how would you imagine that working?

Domain Expert: We would like to be able to set a minimum limit for each product so that we can receive an alert when stock is nearing its end. This would help us ensure that we never run out of a popular product and would also allow us to order more efficiently.

Developer: And how would you like to receive these alerts? By email, SMS or some other method?

Domain Expert: It would be great if we could receive alerts via email as well as a notification in our stock management system.

Developer: Got it. What about the sales and stock history viewing functionality, what type of information would you like to see?

Domain Expert: We would like to be able to see how many products we sold in a given period, what profit was generated per product, and which products are selling best in each period. It would also be helpful if we could look at stock trends over time to help us make better purchasing decisions.

Developer: Ok, and do you have any other features you would like to see in the system?

Domain Expert: It would be very useful if the system could allow us to create and manage purchase orders automatically, based on defined minimum stock quantities and sales trends. It would also be great if we could integrate the system with our suppliers so that we could receive automatic updates on delivery times for new shipments.

## Entities
- Product
- Stock
- Sale
- Orders
- Alert
- Supplier
- Shipping

## Use cases
- Track the entry of a product into stock
- Track the departure of a product into stock
- Sends an alert when the product is running out of stock
- View sales history
- View stock history
- Order new shipments from the supplier
- Sell ​​product
- Receive delivery time updates for new shipments from the supplier
- Create new orders automatically from stock and sales trends
