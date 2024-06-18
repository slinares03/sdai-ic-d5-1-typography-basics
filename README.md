# Solo - Customizing Fonts and Enhancing Styles 💪

**Description:**
Students will independently choose new Google Fonts for the headings and/or paragraph text, apply these fonts, and make additional simple style updates to improve the visual appeal of the site.

## Google Font Suggestions
| **Font Name**           | **Link**                                                 | **Description**                                                                 |
|-------------------------|----------------------------------------------------------|---------------------------------------------------------------------------------|
| **Roboto**              | [Roboto](https://fonts.google.com/specimen/Roboto)       | A modern, clean sans-serif font with excellent readability and versatility.     |
| **Lora**                | [Lora](https://fonts.google.com/specimen/Lora)           | A serif font with a balance of contemporary and calligraphic influences.        |
| **Merriweather**        | [Merriweather](https://fonts.google.com/specimen/Merriweather) | A serif font designed to be highly readable, with a classic yet modern feel.   |
| **Playfair Display**    | [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) | A serif font with a high contrast and elegant design, perfect for headings. |
| **Fredericka the Great**| [Fredericka the Great](https://fonts.google.com/specimen/Fredericka+the+Great) | A whimsical and decorative serif font with a hand-drawn feel.                    |

Using Google Fonts is appealing because they offer a vast selection of high-quality, free fonts that can be easily integrated into websites, enhancing design flexibility and improving the visual appeal of web content.

You'll be tasked with updating the fonts on both pages of the site.

## ToDo list ✅

1. **Introduction:** Choose from one of the recommended Google Fonts for headings and/or paragraphs and discuss why they might fit the site’s theme.

2. **Step-by-Step Walkthrough:**
    - [ ] **Task 1:** Update font styles.
        - **Subtask 1:** Select a new font for headings and/or paragraphs from the provided list.
        - **Subtask 2:** Add the link to the selected font in the `<head>` section of both `index.html` and `about.html`. Replaace or remove links to any `font-family` you are no longer using in your CSS file by removing the appropriate <link> tag from your <head> element.  
        - **Subtask 3:** Update the CSS to apply the selected font to the headings and/or paragraphs.
            ```css
            /* Example CSS Updates */
            h1, h2, h3, h4, h5, h6 {
              font-family: 'Fredericka the Great', cursive; /* Update with chosen font */
            }

            p {
              font-family: 'Roboto', sans-serif; /* Update with chosen font */
            }
            ```
    - [ ] **Task 2:** Enhance other styles.
        - **Subtask 1:** Add hover effects to links and buttons.
            ```css
            /* Example Hover Effect */
            .nav a:hover {
              background-color: #444;
            }

            .card h3:hover {
              color: #ffa07a; /* Hover effect on card titles */
            }
            ```
        - **Subtask 2:** Increase the padding and margin for better spacing.
            ```css
            /* Example Padding and Margin Update */
            .card {
              padding: 1.5em;
              margin: 1.5em;
            }
            ```
    - [ ] **Task 3:** Change the color of your `<a>` elements so that they look better both before and after clicking them.
        - **Subtask 1:** Update the CSS with less specificity so that you're not accidentally overriding your .nav a styles, just like below. **Recall:** Class selectors like `.nav` override element selectors like `a`.
            ```css
            a {
              color: #ff6347; /* Link color */
              text-decoration: none;
              border-bottom: 1px dashed #ff6347; /* Optional underline style */
              transition: color 0.3s ease;
            }

            a:hover {
              color: #ffa07a; /* Hover color */
            }

            a:visited {
              color: #ff4500; /* Visited link color */
            }
            ```




4. **Review:** View the updated site, ensure all changes are applied correctly, and discuss further improvements.

**Reminder:** Use your AI assistant to ask questions and troubleshoot issues. This practice will help you become more independent and capable on teams.

🌟 **Awesome work! You have successfully customized fonts and enhanced the styles of the site.** 🌟


## Additional Resources
- [MDN Web Docs - CSS Font](https://developer.mozilla.org/en-US/docs/Web/CSS/font): Provides detailed information and examples on using CSS font properties.
- [MDN Web Docs - :hover](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover): Learn how to use the `:hover` pseudo-class to add hover effects to your elements.
- [Google Fonts](https://fonts.google.com/): Explore and choose from a wide range of free fonts to use in your projects.