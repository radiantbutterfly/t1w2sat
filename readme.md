# A website built from scratch

~ HTML
~ CSS
~ wireframes
~ git
~ markdown

## HTML 

We started creating the skeleton, then we created the header, linked the CSS and the other two big containers, main and footer.

Header contains a logo, a heading and navigation.

```html 
<header>
        <div class="logo">
            <p>My Logo</p>
            <h1>Personal Training</h1>
            <nav class="nav-items">
                <a href="">Training</a>
                <a href="">About Us</a>
                <a href="">Contact</a>
            </nav>
        </div>
    </header>
```

## CSS

Defined primary and secondary colors, added them to the background and text colors.

Flexbox for the header to align the three elements inside centered and vertically.

```CSS
header {
    background-color: #ff9900;
    display: flex;
    flex-direction: column;
    align-items: center;
}
```
## Wireframes

!["Figma view"] (./images/figma.jpg)
!["Browser view"] (./images/browser.jpg)