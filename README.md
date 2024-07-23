# Desert Format

The **desert** format is a minimalist [Quarto Reveal.js presentation](https://quarto.org/docs/presentations/revealjs/) theme. It is built around the [Reasonable Colors](https://www.reasonable.work/colors/) palettes, Cinnamon and Cerulean, which have the advantage of being high contrast, accessible, and complementary. I like to think of them as providing an approximation to the palette of colors you are likely to encounter on an early evening hike through one of the endless canyons of the American West.  

The main inspiration for this format is Grant McDermott's ["clean"](https://github.com/grantmcdermott/quarto-revealjs-clean) theme. I also got a lot of great ideas from Emil Hvitfeldt's ["slidecraft" blog](https://emilhvitfeldt.com/project/slidecraft-101/). 

## Installing

If you would like to add the **desert** theme to an existing directory:
```bash
quarto install extension kbvernon/quarto-revealjs-desert
```
Alternatively, you can create a new directory and add the **desert** theme to it with: 
```bash
quarto use template kbvernon/quarto-revealjs-desert
```
This will also create an example qmd file that you can use as a starting place for your presentation.

## Format Options

You can add a link on the title page to the associated Github repository, using the yaml option `github: <user>/<repo>`.
```md
---
github: kbvernon/quarto-revealjs-desert
---
```

## Example

For examples of styling and functionality, see the demo at <https://kbvernon.github.io/quarto-revealjs-desert/demo.html>.  

Source code for this demo can be found here: [demo.qmd](demo.qmd).

## To-Do

- Add dark and light modes for the title slide.
- Custom slide templates with useful layouts for figures.