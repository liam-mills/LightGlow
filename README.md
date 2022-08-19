# Light Glow
I found this old project from awhile ago where I realised you can use the CSS [backdrop-filter](https://developer.mozilla.org/en-US/docs/Web/CSS/backdrop-filter) effect to emulate light emission. 
So I set up a small animation which moves a colourful shape around a "glass" cuboid in the middle.

This effect works by having multiple backdrop-filter layers stacked on top of each other, giving the illusion of a 3D object being affected by light.

Uses SASS and Pug to compile. Run `npm i` to install, and `npm run compile` to get compile.
