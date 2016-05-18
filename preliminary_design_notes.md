Probably written in python & flask for easy contribution.

SQL database (just because nosql requires more learning). 

main table columns: ID, Title, Affiliation, pointer to filename, extracted text --- what else? 

ID: sequentially assigned key (or hash?)

author table: just a two-column author ID, mergable on ID so user can query by author and get IDs to yank out of main table.  

tag table: like author table.

Alternative approach is just to use mongodb and json. Probably better for adding more features down the road.  but the price is higher barrier to entry for volunteer contributors, more people know sql than nosql-flavor-of-the-month 