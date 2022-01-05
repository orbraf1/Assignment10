# Assignment 10

### Hey, my name is Or Braf. Those are the main things I did in this assignment:
- I created a new MySQL database called "mydb". Inside this database I created a table called 'users' with the fields from assignment 9 (name, email) + a unique user id. Then I inserted the list of users from assignment 9 to this table.
- Inside 'components' folder I created a blueprint called 'assignment10' and attached it to my website. 
- Inside the blueprint I defined a new route called 'assignment10' which leads to a new template called 'assignment10.html'. This template contains five parts:
    * Insertion form - enables inserting a new users to the table 'users'.
    * Update form - enables updating fields of a specific user (recognized by user_id).
    * Deletion form - enables deleting of a user from the 'users' table according to hid user id. 
    * List of users - displaying the list of users (for the table 'users') below the insertion, update and deletion forms.
    * Message - displaying a message at the top of the page about the last change made in the database by the  insertion, update and deletion functions.