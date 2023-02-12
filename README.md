# Polka

This theme adds some colorful minimalism to Obsidian in light and dark modes, with characteristic dots in the ribbon.

![Preview](polka.png)

## Color Customization

Due to the way the theme shares color values between elements for cohesion, Polka ignores the accent color in your Obsidian settings. You can choose your own accent color for the theme to use in the ribbon and elsewhere but you'll need to [create a CSS snippet](https://help.obsidian.md/Extending+Obsidian/CSS+snippets) and override the `--accent-main` parameter with a raw RGB value. For example:

```
.theme-dark {
  --accent-main: 210, 65, 255 !important;
}
```

You can see the effect of the above in the preview below, which also displays the theme's callout formatting:

![Customization](color_customization.png)

If customizing light mode, use `.theme-light` instead `.theme-dark`.

## Fonts

The user is left to select which fonts are loaded, although Polka is set up to use your default monospace font in table content for better number formatting.

The font displayed in the preview images is Franklin Gothic, which is available as standard on Windows. If you want a good, free alternative, try [Rubik](https://fonts.google.com/specimen/Rubik).

## Plugin Support

In addition to modifying your workspace, Polka's colors are adapted for Obsidian's UI and the whole suite of core plugins. Additional attention has been given to:

- Syntax highlighting in code blocks (Polka uses the built-in color scheme but refines the hues).
- [Calendar](https://github.com/liamcain/obsidian-calendar-plugin).
- [Dictionary](https://github.com/phibr0/obsidian-dictionary).
- [Execute Code](https://github.com/twibiral/obsidian-execute-code).
- [Kanban](https://github.com/mgmeyers/obsidian-kanban).

![Example](code_colors.png)
