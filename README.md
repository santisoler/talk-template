# Template for creating slides using reveal.js

This template uses [reveal.js](https://revealjs.com/) for creating nice looking
slides by only editing a Markdown file, with some html syntax for adding some
cool stuff, like columns, fade-in animations, footnotes and more.

## Content

The template contains the following files and directories:

- `content.md`: Markdown file with the content of the slides.
- `style.less`: define custom CSS classes using [Less](http://lesscss.org/).
- `index.html`: HTML file that can be served to show the slides, also contains
  the configurations for reveal.js.

The `pkg` directory contains all dependencies to run the website: reveal.js,
fontawesome and less. Having these files in the same repository allows to
serve the slides completely offline.


## Serving the slides

Install [livereload](https://github.com/lepture/python-livereload):

```
pip install livereload
```

or

```
conda install livereload -c conda-forge
```

Use `make serve` to start a server at `http://localhost:8000`. The page will
automatically reload the page when you update any of the files in the
repository.

## Acknowledgements

This template is based on the
[`talk-template`](https://github.com/leouieda/talk-template) created by
[Leonardo Uieda](https://www.leouieda.com).

## License

The template (`content.md`, `index.html`, and `style.less`) is licensed under
a Creative Commons Attribution 4.0 International License.
