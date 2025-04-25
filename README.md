Pano 360° Interactive Viewer

A simple and lightweight interactive panorama viewer built with plain HTML, CSS, and JavaScript. Move your mouse around the screen to explore different views — front, left, right, up, and back — giving a basic 360° experience using static images.

> Try it live by opening index.html in your browser.



Features

Interactive background change based on mouse position

Simulates a 360° view using five directional images

Smooth transition between views

Pure HTML/CSS/JS — no dependencies


How It Works

The screen is divided into regions:

Left third → Shows left.png

Right third → Shows right.png

Top third → Shows up.png

Bottom third → Shows back.png

Center area → Defaults to front.png


When your mouse moves across these regions, the background image updates accordingly. When you move the cursor outside the screen, it resets to the front view.

File Structure

Pano-360-degrees/
├── index.html        # Main HTML file with logic
├── front.png         # Front view image
├── left.png          # Left view image
├── right.png         # Right view image
├── up.png            # Upward view image
└── back.png          # Back view image

> Replace the image files with your own visuals for customization.



Usage

1. Clone the repo:

git clone https://github.com/shreyash0019/Pano-360-degrees.git
cd Pano-360-degrees


2. Open index.html in any modern browser.


3. Move your mouse around the screen to interact with the panorama.



Customization

Use your own images (left.png, right.png, etc.) with the same file names.

Adjust sensitivity or region logic in the mousemove event handler in index.html.


Future Enhancements (Ideas)

Add touch support for mobile

Use real 360° panoramic images

Add animation between transitions

Add indicator or navigation arrows


---

Feel free to contribute or fork the project!

