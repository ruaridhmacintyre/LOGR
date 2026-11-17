# LOGR
#### Scottish Woodlands Specific Setup

This guide gives details on setup of specific elements of LOGR.  Some modules are only accessible to users with admin priviledges so will only be relavent to those users.  The level of priviledges will be shown after the modules type as follows
`admin` or `comparment editor`

The modules that users can access in LOGR are as follows:  
[Customers](#01-customers)  
[Delivery Locations](#02-delivery-locations-admin)  
[Suppliers]  
[Landowner]  
[Products]  
[Supplier]  
[Compartments]  
[Users]  



### 01 Customers

`admin`

Every delivery location must be attached to a customer.  Each customer can have multiple delivery locations.  

#### 01.1 Naming Customers

Customer names should be entered exactly as they appear in Navision or on the Companies house.

i.e. "James Jones" should be entered as:

> James Jones and Sons Ltd

or "West Fraser" should be entered as:

> West Fraser Europe Ltd

Please don't add any extra info in brackets.

#### 01.2 Notifications

Do not add any notificaitons to the customer.  Any notificaitons should be added to the Delivery Location only.


### 02 Delivery Locations

`admin`

##### 02.1 Naming

This is where the load will be delivered to and what the driver will see in the driver app, so it should be descriptive.  The name of the customer should come first with a space then ":" then another space before the location.  A shortening of the customer name in this case is ok as long as it's consistent with other delivery locations of the same customer.

The standard syntax would be as follows:

> [customer] : [location]

i.e. "James Jones Lockerbie" or "Annan" should be as follows:

> James Jones : Lockerbie  
> James Jones : Annan  

And "West Fraser Cowie" or "Inverness" should be as follows:

> West Fraser : Cowie  
> West Fraser : Inverness  

Other examples might be:

> AWJ : Castlebridge  
> AWJ : Lockerbie  
> BSW : Dalbeattie  
> Glennon : Windymains  

[Goto to of page](#logr)

