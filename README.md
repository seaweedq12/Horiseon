# 01 HTML, CSS, and Git: Code Refactor

## Task
As first task we were given a code to edit and a user story with an acceptance criteria decribing the changes that needed to made.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the of the structure HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```
## URL

https://seaweedq12.github.io/Horiseon/

## Changes Made

1. The site had no title so a title matching the site was added, also a icon was added

2. Element under **div** were given a semantic HTML element **nav**, **figure**, **section**, **aside**, **footer**.Its important it stays in this order or the look of the html becomes different. stylesheet needed to be edited from **div** to **nav** in the .header section

3. All the images were given a empty **alt** attribute as they have no meaning and is just used for decoration. Screen reader ignore images with empty **alt**

4. In the body element a **min-width** was placed to prevent website collasping out of shape

5. In the stylesheet the location of the **section** code was change to match the order of the HTML code. prior to change the **section** code was located under the **aside** code

6. One of the nav anchor link was broken as a section id was missing which was fixed

7. In the **section** and **aside**, different class were given when the styling used in the element were exactly the same. So the class in each element were unified and the css code was reduced