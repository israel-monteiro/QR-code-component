# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./docs/images/qr%20code%20component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

During this project, I improved my understanding of **HTML structure, Flexbox layout, and CSS styling** while building a simple QR code component.

First, I practiced structuring the content using semantic HTML elements. I created a card component that contains the QR code image, a title, and a paragraph explaining the purpose of the QR code.

```html
<main>
  <div class="card-qr">
    <img src="./src/assets/images/image-qr-code.png" alt="QR code image">
    <h1>Improve your front-end skills by building projects</h1>

    <p>
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </p>
  </div>
</main>
```

I also learned how to use **Flexbox** to center the component on the page. By applying Flexbox to the `body` and `main` elements, I was able to align the card both vertically and horizontally in a simple and clean way.

```css
body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

main {
  display: flex;
  justify-content: center;
  align-items: center;
  flex: 1;
}
```

Another important thing I practiced was styling the card component with CSS. I controlled the width using `min()`, added padding for spacing, and applied `border-radius` to create rounded corners, which improved the visual appearance of the layout.

```css
.card-qr {
  display: flex;
  flex-direction: column;
  width: min(320px, 90%);
  padding: 16px 16px 40px 16px;
  background-color: var(--White);
  border-radius: 20px;
}
```

This project helped reinforce good practices in **layout structuring, CSS organization, and building simple UI components**.


### Continued development

In future projects, I want to continue improving my skills with **Flexbox**. While building this project, I used Flexbox to center elements and organize the layout, but I still want to practice more complex layouts to become more comfortable with it.

I also plan to focus on writing cleaner and more maintainable **CSS**, improving how I structure my styles and components as my projects grow.

By continuing to build small projects like this, I hope to strengthen my understanding of **layout techniques and responsive design**.


### AI Collaboration

During the development of this project, I used AI tools to assist with some parts of the process.

**Tools used:**
- ChatGPT
- Claude

**How I used them:**
- Reviewing the folder structure and project organization.
- Getting suggestions to improve and refactor parts of the code.
- Clarifying questions related to HTML, CSS, and front-end project organization.

**What worked well:**
The tools were especially helpful for improving the project organization and code structure, and for quickly resolving questions during development.

**What could be improved:**
In some cases, the suggestions needed adjustments to better fit the project and the best practices I wanted to follow.

## Author

- Frontend Mentor - [@israel-monteiro](https://www.frontendmentor.io/profile/israel-monteiro)
