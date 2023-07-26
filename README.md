# Bright - HTML

A modern early education theme built with Tailwind CSS.

## Getting started

We have shipped this template using the Tailwind CLI tool in order to get you up and running as fast as possible.

If you would like to setup a development environment with hot reloading, first ensure that Node.js & npm are installed. This theme uses the latest version of Tailwind: tailwindcss v3.3.

First, install the dependencies by navigating to the project directory in your terminal and run

```bash
npm install
# or
yarn install  # if you have Yarn installed
```

This will install all the required dependencies and place them in a folder called `node_modules` in the root directory.

We have added the compiled CSS file to the `<head>` of all the template's HTML files so if you want to rebuild Tailwind’s utility classes to style your content, you simply run the Tailwind CLI tool to scan your template files for classes and rebuild your CSS. We have wrapped the Tailwind CLI tool in a npm script, that way you can do this by running the following command in your terminal:

```
npm run dev
```

This will run the Tailwind CLI in watch mode, that way the `build/css/main.css` file will rebuild everytime you make changes to your HTML files. You can also run

```
npm run build
```

to build your CSS for production and minify your stylesheet.

## Tailwind CSS

This theme is built on top of the Tailwind CSS framework which is installed via npm and used via the Tailwind CLI tool as recommended by the offical Tailwind installation docs (https://tailwindcss.com/docs/installation). If you are not familiar with the Tailwind CSS framework I would recommend you check out the [Tailwind documentation](https://tailwindcss.com/docs).

The entrypoint css file is located at `src/tailwind.css`. This file contains the `@tailwind` directives. Additionally, the stylsheet includes a handful of custom typography classes for headings which use Tailwind’s @apply directive to extract repeated patterns.

We have made an effort to streamline our CSS by primarily using Tailwind's utility classes, supplementing with just a few custom classes that are defined within the `tailwind.config.js` file. Our project includes a unique color palette and a custom typography theme, designed for both light and dark prose content. Furthermore, we have integrated three official Tailwind plugins: `@tailwindcss/forms`, `@tailwindcss/aspect-ratio`, and `@tailwindcss/typography`.

## Build directory

The bulk of the code is located in the `build` directory. Here you will find all of the `html` files at the root of the directory. the images (`build/images`), and the CSS build file after running the Tailwind CLI tool (`build/css/main.css`).

## Javascript

As for JavaScript we use the following third party packages:

- [Alpine.js](https://alpinejs.dev/) for the mobile navigation, dropdown, hamburger menu, and FAQs. We have installed Alpine.js by including its CDN in a `<script>` tag in in the head of our HTML pages.
- [lightgallery.js](https://https://www.lightgalleryjs.com/) for the gallery. The package and its corresponding stylesheet is installed via CDN and only included in the gallery page.

## Font

This template uses the following Google fonts:

- [Roboto](https://fonts.google.com/specimen/Roboto)
- [Gochi Hand](https://fonts.google.com/specimen/Gochi+Hand)

## Icons

The icons used for this theme are part of the [Hero Icons](https://heroicons.com/) and the [Tabler Icons](https://github.com/tabler/tabler-icons) sets that are free to use and published under the [MIT License](https://github.com/tailwindlabs/heroicons/blob/master/LICENSE).

## Images

All of the images used in the template are free to use and are either from [Unsplash](https://unsplash.com/), [Pexels](https://www.pexels.com/), or custom-made.

## License

This site template is a commercial product and is licensed under the [Tailwind Awesome license](https://www.tailwindawesome.com/license).

## Additional Help

If you need additional help setting up the template or have any questions, feel free to contact us at <rodrigo@tailwindawesome.com>.
