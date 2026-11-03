# Week 2: CSS Mastery

## Author
- **Name:** Lynnet Njangiru
- **GitHub:** [@lynnnjangiru](https://github.com/lynnnjangiru)
- **Date:** October 31, 2026

## Project Description

This is my Week 1 portfolio after adding CSS. I made a stylesheet with colours,
fonts and spacing, and then made the pages responsive so they work on a phone
and on a laptop.

I also made practice pages for the box model, flexbox and grid, plus the five
daily challenges.

## Technologies Used

- HTML5
- CSS3
- CSS variables
- Flexbox
- CSS Grid
- Media queries
- Google Fonts
- GitHub Pages

## Features

- Responsive navigation with a menu button on small screens
- Type scale and colour variables
- Hero section with a profile image
- Project cards in one, two or three columns
- Contact form with a sidebar on desktop
- Footer that changes from one column to four
- Hover and focus styles
- Box model, flexbox and grid practice pages
- Five daily challenges

## How to Run

1. Clone the repository.
2. Open `index.html` in your browser.
3. You can also open the folder in VS Code and use Live Server.
4. Make the browser window smaller to see the mobile layout.

## Project Structure

```
week-02-css-mastery/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── styles.css
├── box-model-practice.html
├── flexbox-practice.html
├── grid-practice.html
├── images/
│   └── profile.svg
├── daily-challenges/
│   ├── styles.css
│   ├── day-1-buttons.html
│   ├── day-2-card.html
│   ├── day-3-hero.html
│   ├── day-4-form.html
│   └── day-5-footer.html
└── README.md
```

## What I Did

- Task 3.1: Added a reset, base font styles and heading sizes.
- Task 3.2: Made a page showing the four parts of the box model and a 300px card.
- Task 3.3: Used the type scale variables from the lesson.
- Task 3.4: Made a colour scheme with CSS variables.
- Task 4.1: Built a navigation bar, a row of cards and a footer with flexbox.
- Task 4.2: Built a photo gallery, a magazine layout and project cards with grid.
- Task 4.3: Made the whole portfolio responsive.
- Task 4.4: Added hover and focus styles and checked the spacing.
- Daily challenges: buttons, card, hero, form and footer.
- I used Flexbox Froggy and Grid Garden for extra practice.

## Lessons Learned

- `box-sizing: border-box` is important. Without it my 300px box was 340px
  because the padding was added on top.
- CSS variables are useful when I want to change a colour in one place.
- Flexbox is easier for a row of items. Grid is better when I need rows and
  columns together.
- It is easier to start with the phone layout and then add the bigger screens.
- I need to test the page with the keyboard, not only with the mouse.

## Challenges Faced

**The menu did not open at first.** I put the checkbox after the navigation, so
the `:checked` selector did not work. I moved the checkbox and label before the
nav and then it worked.

**The cards were different heights.** I made each card a flex column and put
`margin-top: auto` on the button so the buttons stayed at the bottom.

**The footer email was too long on a small screen.** It pushed the page
sideways. I added `overflow-wrap: break-word` and checked it again.

**The contact form was too wide.** I put it in a grid and made it two columns
only on desktop.

## Live Demo

[View Live Site](https://lynnnjangiru.github.io/iyf-s12-week-02-lynnnjangiru)

## Practice Pages

- [Box model](box-model-practice.html)
- [Flexbox](flexbox-practice.html)
- [Grid](grid-practice.html)
- [Daily challenges](daily-challenges/day-1-buttons.html)

## Technical Article

The Week 1 article is not published yet. I will add the Dev.to link here when
it is ready.
