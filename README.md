# Minimal Academic

Minimal Academic is a two-column Hugo theme for personal sites. See the live demo [here](https://www.joshuahu.io) and read about my experience [here](https://www.joshuahu.io/blog/first-hugo).

![Minimal Academic Theme screenshot](https://raw.githubusercontent.com/jhu247/minimal-academic/master/images/screenshot.png)

This theme is designed to be simple and unobtrusive, featuring a clean color palette and consistent formatting throughout, with an emphasis on a beautiful hero image as the masthead. Google Analytics and Disqus are supported out of the box.

## Getting started

I'm assuming you've already installed Hugo and have created a new project. You can follow instructions for that [here](https://gohugo.io/getting-started/installing/).

1. In the root folder of your Hugo project, run:

	```bash
	cd themes
	git clone https://github.com/jhu247/minimal-academic.git
	```

2. The `exampleSite` directory contains all of the necessary resources to launch the site. Simple run `hugo server` from here and point your browser to `http://localhost:1313/` to test it out.

3. Copy `config.toml` from `exampleSite` to your project's root folder to use it. Note that you'll need to change the `theme` value to `minimal-academic` for it to work. This is also where you'll change the title of your site, add your own social media links, configure Google Analytics and Disqus, etc.

4. Upload your own avatar and hero image by replacing `portrait.jpg` and `hero.jpg` in `/static/img/`.

5. Create some content! Either copy the `.md` files from `exampleSite` as a template or use the [hugo new](https://gohugo.io/commands/hugo_new/) command.

## Helpful tips

* Running `hugo server` with the `--watch` and `--verbose` flags makes development much faster and debugging much easier.
* Sometimes your browser will cache resources to improve performance, so your changes will not appear. To get around this, on Chrome, control + click the refresh button and it will do a hard fetch of resources.

## Contributing

There's still more to do: 

* taxonomies
* support for other languages
* SCSS with an asset pipeline

Please feel free to submit an issue or create a pull request!

## License

This theme is released under the MIT License. For more information, please read the [license](https://github.com/jhu247/minimal-academic/blob/master/LICENSE).

## Credits

* Initial Hugo template used to get started: [Hugo Academic](https://sourcethemes.com/academic/)
* Layouts used for inspiration: [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) and [Marco Arment's blog](https://marco.org/)
* Avatar photo used in example site: Photo by Philipe Cavalcante on Unsplash
* Hero photo used in example site: Photo by Jeremy Bishop on Unsplash