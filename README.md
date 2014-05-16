# Web Component Mashups at 3 a.m.

## Live Preview

[Live slides](http://robdodson.github.io/sfhtml5-talk) | [Video](https://www.youtube.com/watch?v=75EuHl6CSTo&list=PLOU2XLYxmsILhqgUXAGpusgBMje8Qd6r-&index=8)

## Getting Started

1. Clone the project
2. Run `npm install`
3. Fire up a local server. I like to use [serve](https://github.com/visionmedia/serve)
4. Open the presentation and navigate to http://localhost:[YOUR_PORT_NUMBER]
5. Navigate using left and right arrow keys

## Updating Slides

1. Run `grunt`
2. Open `scripts/md/slides.md`. You can use markdown or HTML in this file. Slides that contain the line `hidden: true` will not show up in the presentation.
3. In the slide titled `about:me` update the presenter information with your social media accounts
4. Replace `images/slides/profile.jpg` with your own photo

## Using Presenter Notes

1. In your browser change the url to http://localhost:[YOUR_PORT_NUMBER]?presentme=true
2. Refresh the page. You will need to authorize the popup.
3. Refresh the page again. Wait for speaker notes to open.
4. You can drive the presentation from the speaker notes using arrow keys

