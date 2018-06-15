## Overview

This was the presentation I gave at the Django Boston Meetup on June 13, 2018
on "Managing Python Package Dependencies".  A PDF of the slides is present in
the root directory, read on if you're interested in the technical details of
how the presentation was made.

## Installation and slide generation

To generate the HTML slides as they were presented:

* `git clone https://github.com/jmbowman/managing_python_package_dependencies.git`
* Install [virtualenv](https://virtualenv.pypa.io/en/stable/), if you haven't
  already done so
* Create and activate a virtualenv (for example, `virtualenv env` followed by
  `. env/bin/activate`)
* `pip install -r requirements.txt`
* `make html`

## Implementation notes

The presentation was written as a single reStructuredText file (`index.rst`).
This was converted to a [reveal.js](https://github.com/hakimel/reveal.js/)
HTML presentation via [Sphinx](http://www.sphinx-doc.org/en/stable/) using the
[sphinxjp.themes.revealjs](https://github.com/tell-k/sphinxjp.themes.revealjs)
extension.

The PDF was saved from the HTML presentation via Chrome using the reveal.js
[print stylesheet](https://github.com/hakimel/reveal.js#pdf-export).

## License

The presentation is made available under the terms of the Creative Commons
[Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/)
license.
