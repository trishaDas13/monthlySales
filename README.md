# monthlySales

Hoisting Link: https://trishadas13.github.io/monthlySales/

<h2> HTML code description: </h2>

This HTML code is a section of a web page that includes a title, a chart generated using Chart.js, and references to external JavaScript libraries. Here's a brief breakdown:

✔ "div class="storage"": This div element appears to serve as a container for the content within this section.

✔ "h1": The main heading, "Monthly Sales Data," is enclosed in an animated text wrapper created with the use of spans. The spans with class names "line line1" and "line line2" seem to be part of an animation effect. The content "Monthly Sales Data" will be animated in some way using the mentioned animation libraries.

✔ "canvas id="myChart"""/canvas": This canvas element is where a chart created using Chart.js will be rendered. It's a dynamic element that can display various types of charts and graphs to visualize monthly sales data.

✔ "script src="https://cdn.jsdelivr.net/npm/chart.js"""/script": This script tag references the Chart.js library, which is a popular library for creating interactive and visually appealing charts and graphs.

✔ "script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"""/script": This script tag references the Anime.js library, which is likely used for animations, as suggested by the classes "line line1" and "line line2."

✔ "script src="./script.js"""/script": This script tag references an external JavaScript file named "script.js." This file likely contains custom JavaScript code for handling interactions, animations, and possibly fetching and processing data for the chart.
<hr>
<h2> CSS code description: </h2>

✔ Universal Reset: The first part includes a universal reset that sets the margin, padding, and box-sizing properties to create a clean and consistent starting point for styling.

✔ Body Styles: The body is styled to occupy the full viewport height (100vh) and is centered both horizontally and vertically using display: flex, justify-content: center, and align-items: center. The background color is set to a dark gray (#313131).

✔ Storage Container: The .storage class styles a container element with text content. It has a fixed width of 600px, is centered, has padding, border-radius, a box shadow, and a gradient background that goes from a light color (#fdfbfb) at the top to a slightly darker color (#ebedee) at the bottom.

✔ Text Animation: The CSS within the h1 tag is used to create a text animation effect. It appears that the text inside the h1 tag is animated, with some of the characters fading in with a line under them.

✔ Text Styling: The text content of the h1 element is styled. The font weight is set to 900 to make the text bold.

✔ Text Animation Setup: The text within the h1 tag is broken into individual letters using <span> elements. Each letter is contained within a .letter class and is displayed as an inline block.

✔ Line Animation: Under each letter, there's a .line element. These lines are initially invisible (opacity: 0) and are absolutely positioned at the left, spanning the full width with a height of 2px. They have a black background color and a transform-origin set to the top left.

✔ Line Positions: There are two lines, .line1 and .line2. One is positioned at the top of each letter, and the other is at the bottom. These lines create a reveal animation where they expand from left to right, giving the effect of the text being drawn.    
<hr>
<h2> JS code description: </h2>

✔ Chart.js Bar Chart:

The code initializes a new Chart.js bar chart with the provided data.
It selects an HTML <canvas> element with the ID myChart to render the chart.

✔ Bar Chart Data:

The chart's data is defined with labels and datasets. The labels represent months (January to December), and the dataset contains sales data for each month.

✔ Styling the Bar Chart:

The code specifies styling options for the chart, such as the background color and border color for the bars.

✔ Anime.js Text Animation:

✔ Anime.js is used to animate the text in an HTML h1 element.
The code selects the .letters class within an h1 element and wraps each letter in a span element. This is done to animate each letter individually.
Text Animation Timeline:

✔ A timeline of animations is created using Anime.js.
The first animation scales and fades in each letter with a slight delay for each letter.
The second animation scales and fades in a line, mimicking a typewriter effect for the text.
The third animation fades out the entire h1 element.
Infinite Animation Loop:

✔ The animations are set to loop infinitely, creating a continuous animation effect.
<hr>
<h2> Summary: </h2>
Overall, this code sets up a bar chart to display sales data and adds a text animation effect to a heading using Chart.js and Anime.js, respectively. To use this code, ensure that you have included the Chart.js and Anime.js libraries in your HTML, and that you have the necessary HTML elements with the corresponding IDs and classes mentioned in the code.
