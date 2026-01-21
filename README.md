🧪 Registration Form README
Overview
A registration form utilizing Tailwind CSS for styling and JavaScript for real-time validation logic.
Validation Specifications
Name: Must not be empty and must contain only alphabetic characters.
Email: Must follow a valid email format (specifically @gmail.com).
Password: Minimum length of 6 characters and must be alphanumeric.
Submit Button: Automatically toggles the disabled state. It remains unclickable until all validation rules pass.
Project Setup
Tailwind Integration: Uses the Tailwind Play CDN for instant styling without a build step.
Logic Flow:
event.preventDefault() stops page refresh on submission.
classList methods (add/remove) toggle visibility of Tailwind's .hidden class.
The disabled property is managed via a dedicated checkForm() function.
File Structure
index.html: Contains the form structure and Tailwind classes.
chem2.png: Background image for the laboratory aesthetic.
<script>: Internal JavaScript handling RegEx and DOM manipulation
