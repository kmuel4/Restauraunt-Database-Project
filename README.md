# Restauraunt-Database-Project
CSC427 software engineering final project

McPearson’s Restaurant in Sometown, NY is an independently owned and operated restaurant (i.e., not part of a restaurant chain like Wendy’s). 
A major problem they face is that they need to manage the inventory of items from which they supply their daily menus. These items are mainly edible stuff, 
but of a varied nature, such as pasta, loaves of bread, steaks, different kinds of liquor, vegetables such as lettuce, tomato, potato, etc., 
bottles of items such as ketchup, mustard, etc. Their main problem is that they order a certain number of items of a particular kind – e.g., 
they order 100 lbs. of potatoes from a supplier, and it arrives on Monday. They want to have an accurate picture of how many pounds of potatoes they have left 
by Friday – in order to determine whether they should re-order potatoes for delivery on next Monday. Without a computerized system, they would have to manually 
go and count/estimate the number of pounds of potatoes left. This would take time off from serving customers, and thus negatively impact their profit margin. 
If they could, instead, simply look up how many potatoes (i.e., how many pounds of potatoes) are left on the computer, which would be great. Even if the pounds 
are not exactly accurate, but close enough, they would be helped. 

Getting into this situation obviously implies that the inventory items should be ‘trackable’ in some way – e.g., 
they should be barcoded (it is, of course, not possible to barcode every potato – you barcode a bag of potatoes). 
More importantly, it implies that whenever restaurant personnel take an item out of inventory – a bag of potatoes,
a bottle of vodka, etc. – they scan the related barcode into the computer and that item is removed from inventory. 

Doing all of this implies that when the restaurant processes an invoice, which indicates what items came in, and those items are there in front of you, restaurant personnel 
have to barcode each item that came in and scan them into the computerized system. The system will then record the date and time each item came in, and the barcode. 
You have to do this for every item you put into inventory, and then, of course, when you take them out, you have to operate as described above. 

Thus, the basic functionality that the envisaged computerized system should provide include: Barcode an item (manually) and scan it into the inventory database on the computer, 
scan it out when you take it out of the inventory, allow the restaurant owner to see how many items of a particular kind he has in inventory (e.g., how many bottles of 
Stolichnaya vodka have I got left?), and see how much it would cost if I want to invoice a supplier (system must keep track of vendors the restaurant deals with, 
and the prices they charge for various items) order a certain number of units of various items from them
