#User-Management-DashBoard 

HTML: The basic structure includes buttons for adding users and an empty <div> (#userList) where users will be displayed. There's also a hidden form (#userForm) for adding or editing users.

CSS: Basic styles are added to make the user interface clean and organized.

JavaScript:

The fetchUsers() function fetches users from the mock backend API (JSONPlaceholder).
The renderUserList() function dynamically renders the list of users in the HTML.
The addUser() and updateUser() functions handle adding and editing users, respectively, through API POST and PUT requests.
The deleteUser() function removes users by sending DELETE requests to the API.
The form allows users to edit or add a new user.
