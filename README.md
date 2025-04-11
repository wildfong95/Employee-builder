## Customization & Styling

- **Fonts:**  
  - **Headers:** Uses **Balgin Condensed**
  - **Body Text:** Uses **Balgin**

  You can change the font weights or swap fonts by modifying the links in the `<head>` of `index.html`.

- **Colors:**  
  The design leverages a dark green background with light cream headers for contrast. The components (cards, buttons, etc.) utilize soft neutral shades and a gentle accent color for buttons. To adjust the colors, update the values in `style.css`.

- **Content:**  
  - Edit the `skills` object in `script.js` to update the skills in each category.
  - Replace `final-image.jpg` with your desired image.
  - Update the portfolio link in both `script.js` and within the final message area in `index.html` or `script.js`.

## Embedding in Adobe Portfolio

To showcase Employee Builder on your Adobe Portfolio, follow these steps:

1. **Deploy Your Project:**  
   You can host your project on GitHub Pages, CodePen, or any other web hosting service.

2. **Get the URL:**  
   For example, if you deploy on GitHub Pages, your URL might look like:  
   `https://yourusername.github.io/employee-builder/`

3. **Embed Using an Iframe in Adobe Portfolio:**  
   In Adobe Portfolio, add a custom code or embed module and insert the following code snippet:
   ```html
   <iframe src="https://yourusername.github.io/employee-builder/" width="100%" height="600" frameborder="0"></iframe>
