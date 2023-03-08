# PacMan-Movement

## Description
A JavaScript animation that displays PacMan's back-and-forth horizontal motion within the bounds of a web page. This animation utilizes an array of four images that represent the different stages of the PacMan's movement, the mouth-open and mouth-closed in both the right and left directions. The running code  calls a function in 300ms intervals that passes four arguments, the PacMan's position & size, direction of motion, and screen edge size, in order to determine which PacMan image is to be sourced for each function call and in what direction it is moving.

## Installation
First, download all files within the repository and ensure that they are all located within the same directory. Then, open the `index.html` file in your web browser (Google Chrome is recommended). 

_**NOTE:** In order to run the "PacMan-Movement" animation, you must download/copy the 3 required files (`pacman.js`, `index.html`, `PacMan1.png`, `PacMan2.png`, `PacMan3.png` and `PacMan4.png`) & store all the files in the same local directory on your machine._
There are two ways to copy the repository files to your local system:
* Download the repository as a zip file to your local machine:  
  * Navigate to the GitHub repository's main page and click the green _'Code'_ button on the right side. 
  * In the menu pop-up, click _'Download ZIP'_. 
* Fork & Clone the GitHub repository to create a local copy:
  * Navigate to the GitHub repository's main page and click the green _'Code'_ button on the right side. In the menu pop-up under **'Clone'**, select your clone type (`HTTPS`, `SSH`, or `GitHub CLI`), and then click the button to copy the URL.
  * Open your system's command-line system (**Terminal** for Mac users). Use the `cd` command to navigate to the system location where you want the cloned repository to exist. In the command line, type `git clone [url]` with the copied URL to finish cloning the repository to your local system.

Once the zip file or cloned repository is copied onto your local system, locate and open the local directory. 

Open your web browser (Google Chrome is recommended), and drag and drop the `index.html` file into your browser window to run the live animation (or, right-click the _`index.html`_ file and select your browser from the _'Open With'_ command).

## How to Use
Once the web page is fully loaded, the animation will appear and should depict the PacMan opening and closing its mouth with each movement and moving from left to right between the screen edges of your window.

## Roadmap
I would like to further proceed in developing out the video game application components beyond the movement of the PacMan character by developing a realistic depiction of the classic game background with the proper animations to create the walls and map canvas area as functional bounds for the PacMan to recognize as movement functionalities similar to that of this application, but on a larger and more complex scale of the actual game map.

## Support
For additional support, contact via email (gabysalgar1314@gmail.com) with specified details regarding questions, issues or concerns.

## License Information
MIT License

Copyright (c) 2023 Gaby Salgar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
