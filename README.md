## Website Performance Optimization portfolio project

View the GitHub hosted pages at: [https://jbranigan.github.io/frontend-nanodegree-mobile-portfolio/](https://jbranigan.github.io/frontend-nanodegree-mobile-portfolio/)

### Part 1: Optimize PageSpeed Insights score for index.html

#### PageSpeed Scores Achieved
* Mobile: 95
* Desktop: 96

#### Optimizations Made:
1. Resize and compress the images
    * Some of the images were quite large, compared to the display size
    * Images weren't compressed
2. Add `media="print"` media query to the `print.css` request
3. Add `async` to the Google Analytics JavaScript request
4. Inline the basic styles from `css/styles.css` and remove the external request
5. Remove the 700 font weight from the Google Fonts request. This weight can be synthesized from 400 in the browser with CSS.
6. Move JavaScript requests to the bottom of the page.
7. Use the Google WebFont Loader to asynchronously pull in and apply the 'Open Sans' font


### Part 2: Optimize Frames per Second in pizza.html

#### Benchmarks
* Time to generate pizzas on load: 17ms - 30ms
* Average scripting time to generate last 10 frames: 0.3ms - 0.5ms
* Time to resize pizzas: 2.6ms - 4.8ms

#### Optimizations made
* Scrolling FPS
    1. updatePositions()
        * 

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
