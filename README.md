# Modular - A theme made for Vesktop

## Introduction

This is one of the first themes that is made exclusively for **Vencord's own client, Vesktop**. It incorporates many of the things I have learned since I started learning about CSS (and modifying Discord clients) in April this year. 

Consider this as my "baby", my first "finished" product that I can contribute to the playground of Discord client mods.

***You heard that right. This theme is only guaranteed to work as expected in Vesktop.*** 

Get the latest build here: [Releases - Vencord/Vesktop](https://github.com/Vencord/Vesktop/releases)

## Features

- High customizability:
  + ***Add a pre-made Nitro theme or background of your choice*** and adjust the brightness, blur as well as transparency
  + **Client global accent** using the HSL scheme
  + A **second accent color** to highlight important elements and add style
  + **Modules** (user panel, member list, guild list etc.) that can be flipped around
  + Adjustable **chat bubble, status and staff tags colors**
  + Adjustable **primary and code font**
  + **Add a custom name on the titlebar** to make the layout more personal
    
- **A revamped look** for many elements, including profile panels and modals, Spotify controls, guild list and many more!
- **Compatibility and quality of life changes** for many of Vesktop's existing plugins
- Several ***add-ons*** are available separately in the `modular.theme.css` file
- Active support (to my ability)
- Some of the elements of this theme are available separately as snippets. Check them out [here](https://github.com/SEELE1306/SEELE1306.github.io/tree/main/Snippets).

## Images

### This is what you will see upon loading the theme for the first time:

![First Load](https://github.com/SEELE1306/SEELE1306.github.io/blob/main/Modular/src/images/Screenshot%202023-09-20%20225845.png)

### Layouts can be customized to these:

![Layout Sample 1](https://github.com/SEELE1306/SEELE1306.github.io/blob/main/Modular/src/images/Screenshot%202023-09-20%20173634.png)
![Layout Sample 2](https://github.com/SEELE1306/SEELE1306.github.io/blob/main/Modular/src/images/Screenshot%202023-09-20%20173847.png)
![Layout Sample 3](https://github.com/SEELE1306/SEELE1306.github.io/blob/main/Modular/src/images/Screenshot%202023-09-20%20174111.png)

## Apply and customize

### Apply
There are several methods to apply this theme:

<details>
  
<summary>Via Local Themes:</summary>

  + Download the file `modular.theme.css` from this repository.
  + Open Settings > Vencord > Themes > Local Themes > Open Themes Folder.
  + Paste the downloaded file into the **themes** folder.

</details>

<details>
  
<summary>Via Online Themes</summary>

  + Open Settings > Vencord > Themes > Online Themes.
  + Paste the following link into **Theme Links**: `https://seele1306.github.io/Modular/modular.theme.css`
  + Enter or mouse-click outside the Online Themes box to apply

</details>

<details>

<summary>Via QuickCSS</summary>

  + Open Settings > Vencord > Vencord > Open QuickCSS File
  + Paste the following line as your **first line (ahead of any other custom CSS)**: `@import url(https://seele1306.github.io/Modular/modular.theme.css);`.

</details>

### Customization
A large part of the following guide is also available inside the `modular.theme.css` file.

To start customizing your layout, copy and paste **lines 10-82** of `modular.theme.css` into your QuickCSS.

Additionally, if you want to use add-ons (Settings Icons and Radial Status), paste these lines at the top of your QuickCSS:
- Settings Icons by [Saltssaumure](https://github.com/Saltssaumure): `@import url(https://minidiscordthemes.github.io/SettingsIcons/SettingsIcons.theme.css);`
- Radial Status by [coolesding](https://github.com/coolesding): `@import url(https://raw.githubusercontent.com/coolesding/shiggycord/v2/Deploy/Radialstatus.css);`
- OnekoDM: `@import url(https://seele1306.github.io/Snippets/OnekoDM/import.css);`

**Catppuccin Colors** are available in this theme for convenience. More about how the colors look like can be found [here](https://github.com/catppuccin/catppuccin).

To apply a color, use the following format: `var(--ctp-{scheme}-{color})`
- **Available schemes** (replace `{scheme}` with these): latte, frappe, macchiato, mocha
- **Available colors** (replace `{color}` with these): rosewater, flamingo, pink, mauve, red, maroon, peach, yellow, green, teal, sky, sapphire, blue, lavender
- For example, the color Latte Sapphire `#209FB5` would be `var(--ctp-latte-sapphire)`

**Discord Nitro gradients** available: aurora, forest, hanami, lofi, mint-apple, mars, neon-nights, retro-raincloud, strawberry-lemonade, sepia,
midnight-blurple, chroma-glow, citrus-sherbert, cotton-candy, crimson-moon, desert-khaki, dusk, retro-storm, sunrise, sunset, under-the-sea 

##  Special thanks to
My theme, at the end of the day, is just a compilation of the many snippets that I have found. I will try my best to credit all the users whose snippets I have ultilized, but if your name does not show up here, feel free to contact me.

### Credits
[coolesding](https://github.com/coolesding), [Saltssaumure](https://github.com/Saltssaumure), [DaBluLite](https://github.com/DaBluLite), [Vendicated](https://github.com/Vendicated), [CodeF53](https://github.com/CodeF53), AkiraSimplex (`akirasimplex` on Discord)

## Issues
You tell me!

