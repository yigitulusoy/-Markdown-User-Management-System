User Management Specifications

The User Management Screen enables administrators to oversee and modify user data. They can create new user accounts, modify existing ones, and remove users from the system. This screen is designed to be user-friendly and clear, making these tasks simple and efficient.


Requirements

The system requires admins to implement operations and adjustments. These should be provided to admins:
1. User List: List of users with the following informations: id, username, email, enabled, role
2. User details: Selected user’s id, username, email, enabled or not, role, etc.
User creation: Allowance for new users with a basic form with the info provided above.

UI Components

Bar: Bar is the head of the table that includes several headers
User Table: Table to list users
User details section: A section that displays user info in more detail with their id, role, username, email, etc
User creation: A sheet where admins can create new users.


UI Behavior

1.User list:
- At first, the table is blank.
- Users are added to this blank table.
- When selecting specific users, the detailed info of the users should be shown in the sheet.

2.User details: 
- Only active when a specific user is selected. Upon selecting, the sheet shows the detailed info of the user.

3.User Creation: 
- At first, the form is blank. Admins can provide the essential information and create a user.
- After filling and confirming the form, the new user is shown in the user list.



# User Management Specifications

## Requirements

1. User List
2. User Details
3. User Creation

## UI Components

1. Bar
2. User Table
3. User details section
4. User Creation Section

## UI Behavior

User Listing
- Initially empty, and the box says there are no users.
- Users can be added to this table and they are listed with basic info.
- Clicking on a user should indicate the user’s row and info, showing them on the user details sheet.

User Details
- Initially the sheet is blank since no user is selected.
- Upon selecting a specific user, the detailed info should be displayed on the sheet.

User Creation
- Creation form is initially empty and admins can enter the information about users.
- After submission, a new user is added to the list.

## Initial Site

The page should initially look like this:
- The bar(navigation) at the top
- User listing table with a comment saying there are no users added yet.
- User details sheet with a comment saying no users highlighted
- User creation form to enter info and create a user.
