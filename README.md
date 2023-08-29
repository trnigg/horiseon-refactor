# Horiseon Refactor 
(```horiseon-refactor``` - Module 1 Challenge)

## Description

The goal of this project was to refactor the HTML and CSS making up the homepage of an SEO consultant in order to facilitate accessibility and usability, while maintaining the current layout and design.

### HTML
- HTML was refactored by removing non-semantic containers and code such as `<div>`, replacing them with semantic counterparts (i.e., `<nav>`, `<main>`, `<section>` etc.)
- A `<title>` element was added, and the heading elements were made to fall in sequential order.
- Images were given `alt` attributes where possible.
    - In the instance of the background image nested within CSS, the element containing this was given a `<title>` instead.
- Code deemed redundant was removed in order to simplify remaining HTML.

### CSS
- Despite the goal of retaining identical layout/styling, the CSS was simplified by grouping together styling by element or other selectors where possible.
    - This resulted in the number of lines being reduced from ~200 to ~140.

## Installation/Usage

- Usage intended as a deployed webpage - no installation necessary.

## Credits

- Starting code (both HTML and CSS) were provided as part of course-work.

## License

MIT License.

Please refer to the license section in the repo for further information.
