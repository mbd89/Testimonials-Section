# Testimonials-Section


Live Site URL: https://mbd89.github.io/Testimonials-Section/

# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 



### Built with

- Semantic HTML5 markup
- CSS 
- FLEXBOX
- Grid
- For styles: 
    Font Family: [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed)

    Colors: Moderate violet: hsl(263, 55%, 52%)
            Very dark grayish blue: hsl(217, 19%, 35%)
            Very dark blackish blue: hsl(219, 29%, 14%)
            White: hsl(0, 0%, 100%)

### Continued development

For this project, the cards are arranged using grid. The pictures, names and the quotes on the first div are arranged using Flexbox. The names and "Verified Graduates" are both spans, there is probably a better way to do this. I used spans so the space between is little. 
Listening for any suggestions to do this better. 


Overall this challenge was not too difficult to complete except it was a little hard for me to make the content fit the entire height of the page. 
Because the style guide says to build this for 1440px wide desktop and my screen is 1280 so I relied on google tools to see the result of the site on 1440px width and 900height. 
There was white space at the bottom of the page, so when i searched google how to remove white space, I found this:
```css
body  {
  height:100%;
}
.container{
  min-height:100Vh;
}

```
Now the problem this code above here creates is now the cards are big so there is a lot of  empty space between the text and the bottom of the divs. So to eliminate the empty space within the cards I wrote a media query that begins at 1380px that increases font size to 22px. 

So i am not too familiar with any units (vh, px etc.), I guess i have a lot of work to do to understand them. 

Maybe another thing I struggled with was to place the quotes that are on the first div with the violet  color at that position.  
I first wanted to position it below the white text with absolute positionning but it moved when I resized the screen. So to fix that I used negative margins on the white text. 
Since the text is placed in the html after the quotes, it naturally stacks on top of it when negative margins are applied to it. 


