# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/design/desktop-design.jpg)

### Links

- Solution URL: [solution URL](file:///I:/Projects/stats-preview-card-component-main/index.html)
- Live Site URL: [live site URL](https://www.frontendmentor.io/solutions/responsive-card-using-flexbox-Mz388h71L0)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
### What I learned

```html
  <body>
    <div class="hero">
      <div class="card">
        <div class="contant">
          <h1>Get <span>insights</span> that help your business grow.</h1>
          <p class="p1">
            Discover the benefits of data analytics and make better decisions
            regarding revenue, customer experience, and overall efficiency.
          </p>
          <div class="numbers">
            <div>
              <h2>10k+</h2>
              <p class="p2">COMPANIES</p>
            </div>
            <div>
              <h3>314</h3>
              <p class="p3">TEMPLATERS</p>
            </div>
            <div>
              <h4>12M+</h4>
              <p class="p4">QUERIES</p>
            </div>
          </div>
        </div>
        <img src="./desktop-design.jpg" alt="human in office" />
      </div>
    </div>
  </body>
</html>
```
```css
@media screen and ( max-width: 800px) {
    .card{
        width:90% ;
        flex-direction: column-reverse;
        text-align: center;
    }
    img{
        width:100%;
        height: 50%;
        border-top-right-radius: 10px;
        border-top-left-radius: 10px;
        border-bottom-left-radius: 10px;
    }
    .hero{
        min-height: 100vh;
        height: auto;
    }
    .numbers{
    display: flex;
    flex-direction: column;
    }
    .numbers div{
        margin-top: 1rem;
    }
}
```
### Continued development

### seful resources

## Author
[KarimAbdelghanyHefnawy1] (https://github.com/karimabdelghanyhefnawy1?tab=following)
 
