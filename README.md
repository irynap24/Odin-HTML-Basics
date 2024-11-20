A simple HTML and CSS built static site, following guidelines of Odin Project.
Project is based on orchids, includes images and info cards about orchids.

Approach for the project:

1. Created button with the class 'signup' which initially displays the text "Sign up".
2. Added an onClick event to the button, which triggers the function toggleButtonText() when clicked.
3. Using JavaScript to manipulate the DOM, the function toggleButtonText() selects the button using document.querySelector('.signup').
4. A check is performed to see the buttons current text using button.textContent.
5. If the button text is "Sign Up", it changes the text to "Thanks!" upon clicking.
6. If the button text is "Thanks!", text is changed to "Sign Up" upon clicking.
