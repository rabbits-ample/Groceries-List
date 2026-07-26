Nothing is going on here yet. 


an app called grocery list, where you submit a picture of a receipt, and then it processes it and turns it into csv or something. 
And then, after that, it puts your data into somethin readable.
and it could keep track of when you buy things, how much you spend on certain things, how long certain things last ( time between buying more) 
it could also evaluate your calories/ vitamin ingestion. 
For example, you submit your receipts for a month, and then it says -> you haven't bought anything that has iron or potassium in it. 
Or you don't eat vegetables, and your vitamins aren't good enough.... And it could also send you reminders.
Or (it could have a smart fridge thing) where you look "what's in your fridge" and then it will say everything that you have bought, and it's aproximated lifetime...
you can also exclude or include weeks into the dataset.

https://developers.google.com/ml-kit/vision/text-recognition/v2/android#1_create_an_instance_of_textrecognizer
https://developers.google.com/ml-kit/tips/installation-paths#key_differences_between_installation_options

This is an image to text package, that we should be able to use (download) directly into the app. (We could make it a server that hosts the code that does all the processing, but I'm lazy and bad)

Work Breakdown Structure
Import Image/Text Reader
Learn how to use the package and use kotlin to handle that
Make a button that says ‘Read’ or something
How are we saving the data -> To a database (prolly not for now?) To the device right?
How do you retrieve from device?
With a database you could create your own object types
For example, we could make a receipt object, and a purchase object
There could be composite key table between those two (the same receipt object can have different purchase objects associated with it. Likewise, a purchase object could be found across multiple receipts. If you buy milk on three different receipts for example )
But if no database, learn how that works... and what the data looks like when you retrieve it.
A page that displays list of receipt texts…

