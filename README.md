# CSS_Task3
README for Nested `<ul>` in HTML with CSS
------------------------------------------

This README provides instructions on how to create and style nested `<ul>` (unordered lists) in HTML using CSS. Follow these steps to correctly structure and customize your nested lists:

1. HTML Structure:
   - Begin by opening the HTML file where you want to create the nested `<ul>` list.
   - Use the `<ul>` element to start the outer list.
   - Inside the `<ul>` element, create `<li>` elements to represent each list item.
   - For each `<li>` element that should contain a nested list, add another `<ul>` element inside it.
   - Within the nested `<ul>` element, add `<li>` elements to represent the items of the nested list.
   - Repeat this structure for any additional levels of nesting you require.

2. CSS Styling:
   - Open your CSS file or create a new one.
   - To remove the default bullet points from the lists, use the following CSS rule:
     ```css
     ul {
       list-style-type: none;
     }
     ```
   - To add indentation to the nested lists, you can use padding or margin properties on the `<ul>` or `<li>` elements. For example:
     ```css
     ul {
       padding-left: 20px;
     }
     /* or */
     li {
       margin-left: 20px;
     }
     ```
   - Customize the styles further by applying different font sizes, colors, backgrounds, or other properties to the `<ul>` and `<li>` elements as desired.

3. Apply CSS to HTML:
   - In your HTML file, link the CSS file by adding the following line of code within the `<head>` section:
     ```html
     <link rel="stylesheet" href="path/to/your/css-file.css">
     ```
   - Replace `"path/to/your/css-file.css"` with the actual path to your CSS file.

4. Save and Preview:
   - Save both your HTML and CSS files.
   - Open the HTML file in a web browser to see the nested `<ul>` list with the applied CSS styles.

Congratulations! You have successfully created and styled nested `<ul>` lists in HTML using CSS. Feel free to experiment with different CSS properties and values to achieve the desired appearance and formatting for your nested lists.
