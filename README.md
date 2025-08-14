# README

## Overview

This project is a simple HTML5 webpage designed to showcase various fundamental HTML5 elements and form features. It includes structured sections demonstrating headings, lists, tables, multimedia integration, and a fully functional contact form.

***

## Features

### 1. Page Heading
- Uses semantic `` for the main page title.

### 2. Lists Section
- Unordered list (``) showing favorite programming languages.
- Ordered list (``) illustrating the steps to build a website.

### 3. Table Section
- Displays a table consisting of web development skills and proficiency levels.
- Semantic ``, ``, ``, ``, and `` elements are used.

### 4. Media Section
- Shows an image with descriptive alt text for accessibility.
- Includes embedded audio with controls.
- Includes embedded video with controls and appropriate fallback text.

### 5. Form Section
- Contact form for user input with:
  - Text input fields (name, email with validation, password with minimum length).
  - Drop-down selection for preferred programming language.
  - Radio buttons for preferred contact method.
  - Checkbox for newsletter subscription.
  - Textarea for additional comments.
- Uses `` and `` to group related inputs.
- Proper labeling for all inputs for accessibility.
- Client-side validation with `required` attributes and input type enforcement.
- Submit button to send form data (currently set to post to `#` which can be updated).

***

## Technical Details

- Document uses HTML5 doctype and language attribute (`lang="en"`).
- Responsive viewport meta tag included for mobile-friendly display.
- Comments are provided throughout the code to clarify the purpose of each part.
- Basic inline table border styling (`border="1"`) is applied for visibility.
- Multimedia elements use appropriate sources and fallback messages.
- Form inputs use semantic HTML5 attributes such as `type="email"`, `minlength`, and `required`.

***

## How to Use

1. Open the `index.html` file in any modern web browser.
2. Navigate through the sections to see examples of lists, tables, media, and forms.
3. Use the contact form to test input validation and form controls.
4. Modify form `action` attribute to connect the form to your server or backend handler.

***

## Extending This Project

- Add CSS for styling and layout improvements.
- Add JavaScript for enhanced form validation or interactive behavior.
- Replace placeholder audio source (`song.mp3`) with an actual audio file URL.
- Connect the form to a backend to handle user submissions.

***

## Summary

This HTML5 showcase is ideal for beginners learning the foundational elements of building webpages, covering content structuring, multimedia integration, and form,  all with semantic markup and accessibility in mind.
