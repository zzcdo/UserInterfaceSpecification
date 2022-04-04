# User Management (UI) Spec

---
* This document has been prepared for software developers who will develop the user interface.

---
* Dashboard(/dashboard)
	* Page will have a "new user" and "save user" button on top.
	* There will be a checkbox for hiding the disabled user.
	* Clicking the "new user" page will split for user info table and the new user input area.
	* Clicking the "save user" inputs will be placed in the table.

* Table(/table)
	* There will be 4 columns, and each column will be sortable and searchable in itself.
		* ID
		* User Name
		* Email
		* Enabled

* New User Input(/input)
	* There will be three types of input. Checkbox, text and drop down list.
	* Text inputs
		* Username
		* Display Name
		* Phone
		* Email
	* Drop down list
		* Guest
		* Admin
		* SuperAdimn
	* Checkbox input
		* Enabled