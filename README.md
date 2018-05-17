# ariaaustralia

##ShoppingCart
Can only be used by the signed in user
1>when user create their account for the first time, it will create the shopping cart record in the db primary key is the userId
2>when user deleted their account shopping cart will also be deleted

interface:
1>add item to shopping cart        (post)
2>delete item from shopping cart   (delete)
3>modify item in the shopping cart  (patch)
4>check out shopping cart           (post)
5>retrieve shopping cart by userId   (get)


##User Management
user has 5 classes: SuperAdmin, Admin, Employee, SVIP, VIP, Normal
interface:
1> create user  (post)
2> modify user  (patch)
3> delete use   (delete)
4> query user   (get)
5> list user    (get)

user table: userId is primary key
each user has one shopping cart stored in the db


##Order Management

interface:
