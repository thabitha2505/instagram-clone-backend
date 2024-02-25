
# instagram-clone-backend
**Project Overview:**
**Objective:** To create a basic user authentication system for a web application.
**Features:**
**Toggling Suggestions Visibility:**
The code listens for the DOMContentLoaded event to ensure that the DOM is fully loaded before executing.
It selects the "Follow All" button and all suggestion containers.
When the "Follow All" button is clicked, it toggles the visibility of all suggestion containers by adding or removing the hidden class.
**Toggling Follow/Unfollow Buttons:**
Similar to the first part, it listens for the DOMContentLoaded event.
It selects all follow buttons.
When a follow button is clicked, it toggles the text content between "Follow" and "Unfollow".
This part could be extended to include actual follow/unfollow functionality.
**Toggling Heart Icons:**
It listens for the DOMContentLoaded event.
It selects all heart icons within post footers.
When a heart icon is clicked, it toggles the clicked class to visually indicate whether the post has been liked or not.
**Login Form Submission:**
It listens for the DOMContentLoaded event.
It selects the login form.
When the login form is submitted, it prevents the default form submission behavior.
It retrieves the username and password values from the form.
For demonstration purposes, it assumes that the credentials are valid and redirects to the homepage (replace 'homepage.html' with the actual URL of your homepage).
**Login Form Validation (Inline HTML):**
This function validateLoginForm is an inline JavaScript function used directly in the HTML form.
It retrieves the username and password values from the login form.
It checks if the username and password match a predefined value (e.g., "user1").
If the credentials are correct, it alerts "Login successful!" and redirects to the homepage. Otherwise, it alerts "Invalid username or password."
**Register Form Validation:**
It defines a function validateRegisterForm to validate the register form.
It retrieves the username, email, and password values from the register form.
It checks if all fields are filled in and if the email format is valid.
If the form passes validation, it returns true, allowing form submission. Otherwise, it returns false and shows an alert with the appropriate error message.
**Accessibility and Responsiveness:**
Ensured the forms are accessible and usable across different devices and screen sizes.
Applied responsive design principles to maintain readability and usability on smaller screens.

![Screenshot 2024-02-25 161303](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/3d996f9c-dd88-48cb-88bc-6b895d7fed99)
![Screenshot 2024-02-25 161328](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/c12833a0-3054-437e-ae97-f7e624145691)
![Screenshot 2024-02-25 161847](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/0dd46ce5-d36f-49e8-b8d8-2acadb4f3df0)
![Screenshot 2024-02-25 161935](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/dc3cc8ad-b72a-4507-aaff-e46db7dd28f7)
![Screenshot 2024-02-25 161429](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/58019199-0cf0-4537-a25d-a53fbec3b35c)
![Screenshot 2024-02-25 161704](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/591de797-4675-400f-82dc-6b5d128cbbf0)
![Screenshot 2024-02-25 162554](https://github.com/thabitha2505/instagram-clone-backend/assets/118505858/980e9b56-00ad-47d1-9dc4-57a8f01246bf)
