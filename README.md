Foundry Progress
===============

A family of animated spinners, loaders and progress bars for [Foundry ∞](https://github.com/thoughtbot/foundry).

- The icons are pure SVG, no javascript and CSS required
- They are all 50x50 pixels, ensuring that you can swap one spinner out for another
- The markup is easy to edit and follows [thoughtbot's guides](http://github.com/thoughtbot/guides)
- The `<svg>` includes an `id` and `class` matching the filename, for targetting with CSS
- The paths inside (`<circle>`, `<rect>`, `<path>`, etc) include a class `shape` to make styling even easier

---

### How do I style the icons?

By adding something like this to your CSS:
```css
.progress-006 {
  height: 25px;
  width: 25px;
}

.progress-006 .shape {
  fill: #C32F34;
}
```
