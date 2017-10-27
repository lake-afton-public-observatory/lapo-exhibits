# Lake Afton Public Observatory Interactive Exhibits
Web-based interactive slideshows and infographics for tablets and computers at the Lake Afton Public Observatory.

## Presentations
The purpose of this repository is to provide an open-source codebase for a group of interactive displays and exhibits at Lake Afton Public Observatory. Initially this
repo was simply a placeholder for converted PowerPoint but we can do a lot more. Feel free to update information on existing slides, add new slides or entire presentations, or
even add completely new functionality. Examples could be:
- Videos
- Games
- Slideshows
- Quizzes

## Working with the source code
The source files are written in [EJS](http://ejs.co/) and we are using [Harp.js](https://harpjs.com/) to build those files.
All the sources are inside the `_src` directory. When you run `harp compile _src .` the contents of the `_src` directory will be compiled and copied to the root directory of the project.
Is recommended to put all the files inside the `_src` directory, since the files in the root directory will be replaced each time the files are compiled.

Before installing Harp make sure you have [NodeJS](https://nodejs.org) installed.

To install Harp, run the following command:

```
sudo npm install -g harp
```

## Working with the source code

1. Clone it to your local machine however you like
2. Place the updated [binaries](#binaries) in the `/img/` and/or `/video/` folders
3. Run `harp server _src` to view/test
4. Edit code
5. Run `harp compile _src .` to build
6. Push code

Since there's currently no internet out at the observatory, this repo will have to be manually installed on the on-site server, so expect a delay between when you push changes and when they show on the tablets at LAPO.

## Binaries
- A bunch of images and videos are required for this project. They can be [downloaded here](http://bit.ly/2bII3mF) and placed in the `img` and `video` folders.
- Try to keep photos no larger than 1280x800

## Code
- Reveal.js code documentation can be found on [Github](https://github.com/hakimel/reveal.js/)
- Please use existing exhibits as a template.
- If you want to add a new feature discuss you may submit a pull request but we'd love to chat about it first. Send questions to [Seth Duncan](sduncan@lakeafton.com) or [Michael Neth](mneth@lakeafton.com).

## Technology
- These presentations will be running on Raspberry Pi powered 10" touchscreens running 1280x800 resolution. Please take these constraints into consideration.
- Powered by [Reveal JS](http://lab.hakim.se/reveal-js/#/)
- Using Bootstrap 4, jQuery 3.0.0 slim, Popper.js

## Branding
In an effort to maintain consistent, professional branding, please use the logos and brand standards. If you have any questions or need feedback, Andrew Stephens has offered to advise.

- [**Logos/Brand Standards Download**](http://bit.ly/2aNUfSN)
- **Dev Contact:** [Seth Duncan](sduncan@lakeafton.com)
- **Git Contact:** [Michael Neth](mneth@lakeafton.com)
- **Branding Contact:** [Andrew Stephens](artandsalsa@gmail.com)
