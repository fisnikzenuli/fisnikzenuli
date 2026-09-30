# fisnikzenuli.github.io

My portfolio website, live at **[fisnikzenuli.github.io](https://fisnikzenuli.github.io)**.

## How it works

- One HTML file with no framework and no build step
- The project previews load each live site in an `iframe`, rendered at real desktop (1280px) or phone (390px) width and scaled down to fit with a CSS `transform`, so visitors can switch sizes and use the real site
- Previews stay locked until clicked, so scrolling the page on a phone doesn't get stuck inside a preview
- The intro types out the name as HTML, then shows the styled heading. It's skipped for visitors who turn on "reduce motion" in their system settings
- Responsive layout with CSS Grid and `clamp()` for type sizes

## Built with

HTML, CSS and JavaScript. Hosted on GitHub Pages.
