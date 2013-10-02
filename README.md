Jeet 3 - SCSS port
---

Refer to http://jeetframework.com for usage docs.

Installation
---

- Install [Ruby](http://rubyinstaller.org) (if you're on Windows)
- Add Ruby to your PATH if you're on Windows
    - Find the folder Ruby/bin folder (usually under C:/), copy this path
    - Right click on "My Computer", "Properties"
    - Advanced System Settings
    - Environment Variables
    - Global
    - Path
    - Append a semi-colon and the path to Ruby/bin
- Install [Compass](http://compass-style.org/install/)
- Open up a terminal and type `git clone https://github.com/CorySimmons/jeet.git && cd jeet && git checkout scss`
- `./watch`
- Open `index.html` in the browser of your choice and activate LiveReload by opening Settings > Tools > Extensions and checking `Allow access to file URLs` then clicking the icon (the dot in the middle should be dark)
- Edit `css/custom.scss`
- Enjoy
Usage with Roots
---

[Roots](http://roots.cx) is a static site compiler that cooperates nicely with jeet. It makes creating and watching your project a smoother and less manual process, and adds loads of features you can take advantage of like precompiled templates, a variety of supported languages (jade, coffeescript, etc.), dynamic content for buulding things like blogs, and livereload in development. To install roots and the roots jeet template follow the steps below:

- `npm install roots -g`
- `roots template add jeet https://github.com/jenius/jeet-template`

Now to create a new roots project with the jeet template and grid, follow these steps:

- `roots new your_project_name --jeet`
- `cd your_project_name`
- `roots watch`

Note
---

We're currently working on another npm package and will be expanding on the doc with screencasts and such. To be honest, I just wanted to start using Jeet 3 for a few personal projects of mine. Jeet 2 is still available under the [Jeet2 branch](https://github.com/CorySimmons/jeet/tree/jeet2) so you can download it and use `jeet watch` in those project directories.

