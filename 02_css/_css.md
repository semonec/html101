# CSS

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language.

The final style for an element can be specified in many different places, which can interact in a complex way. This complex interaction makes CSS powerful, but it can also make it confusing and difficult to debug.

Three main sources of style information form a cascade.
- The browser's default styles for the markup language.
- Styles specified by a user who is reading the document.
- The styles linked to the document by its author. More details about this way are described below.

## How to add styles to the page?

There are three common ways for adding styles to the HTML page.

**External Style Sheet**

Included as an external file using `<link>` element inside the `<head>` section. File must be saved with `.css` extension.

```html
<head>
  <link rel="stylesheet" href="style.css">
</head>
```

**Internal Style Sheet**

Defined within the `<style>` element, inside the `<head>` section.

```html
<head>
  <style>
    .label-error {
      color: red;
    }
  </style>
</head>
```

**Inline Styles**

To use inline styles, add the style attribute to the relevant element.

```html
<p style="color:red;">I want to be red.</p>
```
