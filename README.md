# ADMIN INTERFACE

The above module here discusses the interface of that the admin will be using.Primarily, the idea of this project is to reduce the job of Shekhar Bhai as much as possible and this interface will try to achieve that.


The admin interface will perform these following **key tasks**:

   - Have a live display of all the orders
   - Cancel the orders as per requests
   - Live update of availability of food items in canteen
   - Offline Token entry
   - Virtual money addition


As soon as a user places an order, the token number is generated for that user and that same token number, along with the order is displayed on the admin’s page. We will be displaying the order in FIFO manner, as in the orders placed first are on top and as orders are added, they keep getting added at the end. As soon as the order is delivered, they are removed from the list. 


The admin also has the power to cancel orders on request. If a certain user places an order and later for any reason wants to get a refund, then the user will have to request the admin to cancel the order. The user will have to show the token to the admin from his device. The admin, on his discretion, will cancel the order, by clicking on the cancel order button for that token number and the order would be cancelled.


The admin’s other responsibility is also to keep updating the current food items left in the canteen


Not everyone would be using the app, and so as to allow the people to also place orders offline, the admin would be entrusted with the responsibility to enter those orders in the order queue. When anyone places the offline order, the admin will enter its details of the order . So as to minimise time , we will have to reduce number of taps. Finally, after the order details entry into the system is done, the admin will choose a plastic token from his available tokens and give it to the user. He will enter the number of that plastic token in his system and place the order. Now, this offline order will be added to the order queue which is present online. 


Also, the admin would be responsible for adding virtual money into the user account which can be done by taking the roll number or any other unique identification from the user, and by adding the certain amount of money into his account.

For an idea on git please this read this : https://gist.github.com/ythej/3e05c949bb0b8d393b57
