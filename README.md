
####RUN MOBILE PORTFOLIO
 
* Open index.html on your browser
* Click on the projects links to read about them
* On the pizza.html you can: click on the buttons to check the menu, our ingredients, locations and contacts, you can pick a random pizza and you can change the pizza sizes on the slider.


####Changes made and results in index.html (initial result: 30/100; 28/100 -- timeline: 11s )
 
* Added the print media query to print.css -- 8,66s
* Made analytics async -- 6,72s
* Pizzeria.jpg resize and save for web -- 88/100; 74/100 + pizzeriasmall.jpg added for index.html
* Removed googleanalytics.js javascript and made it async -- same result
* Removed all the unnecessary classes in style.css and inlined it - 90/100; 88/100 (around)
* Used WebfontConfig for the font 96/100; 94/100 
* FINAL RESULT: 96/100; 94/100 timeline: 517ms

####Changes made and results in main.js (initial result: 10 frames: 34/24ms, time to resize pizzas: 88.86ms )
 
* Reduced the amount of pizzas being generated in the background from 200 to the necessary 22 (added one more row just in case the formats are different) so 8x4=32 -- 10 frames: 5/6ms
* Created variables for the updatePositions function, removed them from the for loop so they are only calculated once --- 10 frames: 2/0.2 ms
* Created variabes for the changePizzaSizes function 
* Changed querySelectorAll to getEmentsByClassName based on: https://jsperf.com/getelementsbyclassname-vs-queryselectorall/18 --- time to resize pizzas: 0.26 ms
* FINAL RESULT: 10 frames: 2ms (first) 0.2 ms / time to resize pizzas: 0.26


### Optimization Tips and Tricks
* [Optimizing Performance](https://developers.google.com/web/fundamentals/performance/ "web performance")
* [Analyzing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/analyzing-crp.html "analyzing crp")
* [Optimizing the Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/optimizing-critical-rendering-path.html "optimize the crp!")
* [Avoiding Rendering Blocking CSS](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html "render blocking css")
* [Optimizing JavaScript](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html "javascript")
* [Measuring with Navigation Timing](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/measure-crp.html "nav timing api"). We didn't cover the Navigation Timing API in the first two lessons but it's an incredibly useful tool for automated page profiling. I highly recommend reading.
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/eliminate-downloads.html">The fewer the downloads, the better</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer.html">Reduce the size of text</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization.html">Optimize images</a>
* <a href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching.html">HTTP caching</a>

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>

### Sample Portfolios

Feeling uninspired by the portfolio? Here's a list of cool portfolios I found after a few minutes of Googling.

* <a href="http://www.reddit.com/r/webdev/comments/280qkr/would_anybody_like_to_post_their_portfolio_site/">A great discussion about portfolios on reddit</a>
* <a href="http://ianlunn.co.uk/">http://ianlunn.co.uk/</a>
* <a href="http://www.adhamdannaway.com/portfolio">http://www.adhamdannaway.com/portfolio</a>
* <a href="http://www.timboelaars.nl/">http://www.timboelaars.nl/</a>
* <a href="http://futoryan.prosite.com/">http://futoryan.prosite.com/</a>
* <a href="http://playonpixels.prosite.com/21591/projects">http://playonpixels.prosite.com/21591/projects</a>
* <a href="http://colintrenter.prosite.com/">http://colintrenter.prosite.com/</a>
* <a href="http://calebmorris.prosite.com/">http://calebmorris.prosite.com/</a>
* <a href="http://www.cullywright.com/">http://www.cullywright.com/</a>
* <a href="http://yourjustlucky.com/">http://yourjustlucky.com/</a>
* <a href="http://nicoledominguez.com/portfolio/">http://nicoledominguez.com/portfolio/</a>
* <a href="http://www.roxannecook.com/">http://www.roxannecook.com/</a>
* <a href="http://www.84colors.com/portfolio.html">http://www.84colors.com/portfolio.html</a>
