# User Management Screen

* Home Page (/)

    * Header
      * Horizontal Buttons and Checkbox
      <button name="button">+New User</button> [Open a new user registration field <- if clicked]
      <input type="checkbox"><label for="Hide Disabled User">Hide Disabled User</label>
      <button name="button">Save User</button> [Saves user and returns registered users table <- if clicked]
    
    * Body
      1. Registered Users Table

      * This part of the page contains the registered users table.
      * The table can be sorted by all columns ascending or descending.

        | ID 	| User Name 	  | Email 	              | Enabled 	|
        |----	|-----------	  |-------	              |:-------:	|
        |   1 |Adminuser      |admin@piworks.net      |  true     |
        |   2	|Testuser      	|testuser@piworks.net   |  true     |
  
      2. New User Registration Section
      
      * This part of the page contains the new user registration section.
      * Opens only [+New User button <- if clicked]
      * The section should appear on the right side of registered users table.
      * Input box and checkbox fields will be created for information.
      * Closed [Save user button <-if clicked]
          
          * Username : <input type = "text" id = "username" name = "username"/>
          * Display Name : <input type = "text" id = "displayname" name = "displayname"/>
          * Phone : <input type = "tel" id = "phone" name = "phone"/>
          * Email : <input type = "text" id = "email" name = "email"/>
          * User Roles : <input type="text" name="userroles" list="userroles" placeholder="Select user roles...">
              <datalist id="userroles">
                <option value="Guest">
                <option value="Admin">
                <option value = "SuperAdmin">
              </datalist>
          * Enabled:  <input type="checkbox"> 



