# Google Search Front-End

## Youtube Link to View
https://youtu.be/9kpBTUsJce8

## Description
This project is a front-end implementation for Google Search, including Google Image Search and Google Advanced Search, styled with **Sass** for enhanced maintainability and design.

## Features
1. **Google Search Page**:
   - A search bar (`name="q"`) for entering queries.
   - Buttons for:
     - **Google Search**: Displays the standard Google search results.
     - **I’m Feeling Lucky**: Redirects directly to the first result using `btnI=1`.
   - Styled with centered input fields and responsive buttons.

2. **Google Image Search**:
   - A search bar (`name="q"`) for querying images using the Google parameter `tbm=isch`.

3. **Google Advanced Search**:
   - Input fields for advanced queries:
     - All these words (`name="as_q"`).
     - This exact word or phrase (`name="as_epq"`).
     - Any of these words (`name="as_oq"`).
     - None of these words (`name="as_eq"`).
   - Labels and input fields are aligned using **Flexbox**.

## Sass Styling
- **Global Styles**:
  - Reset default margins, paddings, and box-sizing for all elements.
- **Reusable Variables**:
  - `$transition-time`: Defines a consistent transition duration for hover effects.
  - `$hover-grey`: Used for hover colors.
- **Button Styling**:
  - Buttons are styled with shadows, rounded corners, and smooth hover transitions.
  - Colors and hover effects maintain consistency.
- **Input Field Styling**:
  - Rounded input fields with consistent box shadows.
  - Focus effects with distinct outlines for better accessibility.
- **Advanced Search Layout**:
  - Labels and inputs are horizontally aligned with proper spacing (`label { margin-right: 20px; }`).
  - Responsiveness is supported using Flexbox and media queries.

## Technologies Used
- **HTML5** and **CSS3** for structure and styling.
- **Sass** for dynamic, maintainable styling.
- **Google Search Parameters**:
  - `q`: Query for all search types.
  - `tbm=isch`: For image search.
  - `btnI=1`: For "I'm Feeling Lucky."

## Usage
1. Open the `index.html` file to access the Google Search page.
2. Use the navigation links to explore Image Search and Advanced Search.
3. Enter queries in the search bar and test:
   - **Google Search** for standard results.
   - **I’m Feeling Lucky** for direct redirection to the first result.

## Future Improvements
- Enhance responsiveness for smaller screens using additional media queries.
- Expand styling with more reusable Sass variables and mixins.
- Add further support for additional Google search parameters.
