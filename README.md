# A-Frame workshop | WebVR

Materials + challenge from the [A-Frame](https://aframe.io/) Webinar @ Ironhack Madrid 2021 by [Germán Álvarez](https://www.linkedin.com/in/german-alvarez-dev)

## Contents

Here you'll find several A-frame scenes to enjoy, including shapes, textures, models from [SketchFab](https://sketchfab.com/), external resources from the community and interaction examples (both fuse and mouse). Don't hesitate to visit [A-Frame](https://aframe.io/) docs to expand your knowledge!

**Remember**: you also have all the examples we used at the Webinar [available on Codepen](https://codepen.io/collection/zxYOYZ).

## Installation

Clone this repo, or download the files using the "Code" green button at the top. 

All files run on your browser, but to properly experience them you'll need to enable a local server on your computer. [A-frame docs](https://aframe.io/docs/1.2.0/introduction/installation.html) has many suggestions about how to archieve this, but if you are familiar with NodeJS I suggest you [live server](https://www.npmjs.com/package/live-server) package.

Also, you can always use each file content's on Codepen, just paste the `<body>` contents on a new Pen, and don't forget to include before Aframe CDN as we did [on the examples showed in the Webinar](https://codepen.io/collection/zxYOYZ).


## Extra resources for A-frame

### Inspiration
- A-frame showcase: https://webvr.directory/
- A-frame examples: https://aframe.io/aframe/examples/
- A-painter: https://aframe.io/examples/showcase/a-painter/
- Bolerplates for A-frame: https://altspacevr.github.io/aframe/examples/
- A-frame School: https://github.com/aframevr/aframe-school

### Collections
- A-frame components: https://github.com/supermedium/superframe
- A-frame extras: https://github.com/donmccurdy/aframe-extras

### External resources (environments)
- Enviroments component: https://github.com/supermedium/aframe-environment-component
- Shooter kit: https://github.com/supermedium/aframe-super-shooter-kit

### External resources (components)
- Particles: https://www.npmjs.com/package/aframe-particle-system-component
- Orbit controls: https://tizzle.github.io/aframe-orbit-controls-component/

### Frameworks
- Aframe React: https://www.npmjs.com/package/aframe-react

### Aumented Reality
- Aframe AR: https://aframe.io/blog/arjs/

## Challenge: full VR interactive videogame

Check the `interaction-programming.html` file included on the repository: that's how to solve interaction programatically!  Now, create a full VR interactive experience:
- Include several spheres floating around you.
- Use the `animation` Component to create light movements on each sphere [more info](https://aframe.io/docs/1.2.0/components/animation.html)
- Develop a cuastom Component using the `.registerComponent()` built-in method, and attach it to every sphere so after 500ms they change their texture [more info](https://aframe.io/docs/1.2.0/introduction/writing-a-component.html#:~:text=Registering%20the%20Component%20with%20AFRAME.&text=Components%20are%20registered%20with%20AFRAME,object%20of%20methods%20and%20properties.).
- Include a counter through the text entity to show the progress [more info](https://aframe.io/docs/1.2.0/components/text.html).
- Explore the amazing A-frame Universe to include [sound](https://aframe.io/docs/1.2.0/components/sound.html) and [light](https://aframe.io/docs/1.2.0/components/light.html) that interact with the user's actions.

I hope you enjoy this amazing VR stuff.

Catch me up @ [Linkedin](https://www.linkedin.com/in/german-alvarez-dev), and of course @ [Ironhack Madrid](https://www.ironhack.com/).


