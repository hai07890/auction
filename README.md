# auction
Auction project

Create the models which you will use for the auction site (as eBay).
The items model should contain four columns:

o An integer id, which is the primary key

o A name string, which cannot be null

o A description string, which cannot be null

o A start_time DateTime

The user model should contain three columns:

o An integer id, which is the primary key

o A username string, which cannot be null

o A password string, which cannot be null

The bid model should contain two columns:

o An integer id, which is the primary key

o A floating-point price, which cannot be null

Extend your auction.py file to model the relationships between your
User, Bid and Item classes. The models should be related according
to the following rules:

o Users should be able to auction multiple items

o Users should be able to bid on multiple items

o Multiple users should be able to place a bid on an item

You will need to delete and recreate your database before making the
changes to the models. To do that you can run: dropdb auction &&
createdb auction

When you are happy with your classes, test them out by trying to:

o Add three users to the database

o Make one user auction a baseball

o Have each other user place two bids on the baseball

o Perform a query to find out which user placed the highest bid
