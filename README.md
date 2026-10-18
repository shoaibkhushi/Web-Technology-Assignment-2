
# Shoaib Portfolio Website

## 1. What Is CSS and Its Benefits?

CSS stands for Cascading Style Sheets. It is a stylesheet language used to control the appearance and layout of HTML web pages. CSS allows developers to customize colors, fonts, spacing, borders, backgrounds, tables, and responsive layouts. Its main benefits are improved website design, consistent styling, easier maintenance, code reusability, and better user experience across different screen sizes.

## 2. CSS Selector, Property, and Value

Example from the website:

```css
.project-section {
    padding: 28px;
}
```

- **Selector:** `.project-section` selects HTML elements with the class `project-section`.
- **Property:** `padding` defines the space inside an element, between its content and border.
- **Value:** `28px` specifies 28 pixels of internal spacing.

## 3. Types of CSS

- **Inline CSS:** Written directly inside an HTML element using the `style` attribute. It is used in this website for the header, navigation, and About section.
- **Embedded CSS:** Written inside a `<style>` element in the HTML document. It styles the projects, course tables, events, and tour packages.
- **External CSS:** Written in a separate `.css` file and connected using a `<link>` element. The `form.css` file contains the registration form's styling.

## 4. Evolution of CSS

- **CSS1:** Introduced basic styling features such as fonts, colors, text formatting, margins, and padding.
- **CSS2 and CSS 2.1:** Expanded CSS with positioning, media types, and improved layout and styling capabilities. CSS 2.1 clarified and refined earlier specifications.
- **Modern Modular CSS:** CSS is now developed through separate modules, including Flexbox, Grid, Media Queries, and Selectors. These modules support responsive layouts and advanced design features.

## 5. Browser Compatibility

Browser support matters because different browsers may interpret or display CSS features differently. Testing helps identify layout problems, unsupported features, and inconsistent behavior.

**Browsers tested:** Testing has not yet been confirmed. Open `index.html` in Google Chrome and Mozilla Firefox, check the layout and registration form in both, and update this section with your actual results.

## 6. Semantic and Non-Semantic HTML

- **Semantic HTML:** `<header>` describes the introductory section of the website, while `<nav>` identifies the navigation links.
- **Non-semantic HTML:** `<div>` is a generic container that does not describe the meaning of its content by itself.

Semantic elements improve accessibility, readability, and document structure.
