## Website Performance Optimization portfolio project

The main goal of this project is optimization: optimize the critical rendering path and make this page render as quickly as possible by applying different techniques.

To get started, check out the repository and inspect the code.

### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```


Applied technics to the file index.html:
-- inlined css;
-- added viewport tag;
-- used async font import;
-- minified css;
-- reduced size of the images;
-- moved js scripts to the bottom. 


#### Part 2: Optimize Frames per Second in pizza.html

To optimize views/pizza.html, there is modified views/js/main.js until 60 frames per second rate.

Applied chages to the file main.js:
-- changed update background function;
-- removed abnormal heavy size calculations from pizza size function;
-- changed the number of background pizzas according to the user's viewport size;
-- used faster method for css translation in updatePositions function.
-- also added some default chages in pizza.html file.


