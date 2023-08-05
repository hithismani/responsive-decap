# Adding Mobile Responsiveness To Decap CMS/Netlify CMS

This repository provides a solution to add mobile responsiveness to Decap CMS/Netlify CMS, allowing you to create a more user-friendly experience for visitors accessing your content from mobile devices.

## Background

This project is inspired by a [gist](https://gist.github.com/searls/7fd2c3223571a58a81006e7da66bd064) created by Justin Searls, which served as a valuable starting point for addressing the mobile responsiveness issue in Decap CMS/Netlify CMS.

## Prerequisites / Assumptions

Before proceeding with the implementation, please ensure the following:

- You've already set up Decap CMS for your project.
- You're looking for a functional implementation that focuses on mobile views, rather than retaining all UX elements on desktop. (This CSS file targets mobile views only.)
- You understand that attribute selectors (i.e., selectors with *=) are known to be relatively slow. However, for this specific use case, they offer a practical solution to achieve mobile responsiveness without drastically impacting performance.
- You understand that this file *may* conflict with any official solution by DecapCMS that may come up in the future.

## Installation

### Option 1: Manual Installation

Follow the step-by-step guide on how to install the mobile responsiveness for Decap CMS/Netlify CMS manually. The guide can be found at:

[Mobile-Optimized Decap/Netlify CMS Installation Guide](//manikumar.in/blog/mobile-optimized-decap-netlify-cms)

### Option 2: Via jsDelivr CDN

You can easily add mobile responsiveness to Decap CMS/Netlify CMS by linking the pre-built CSS file hosted on the jsDelivr CDN. Simply include the following link in the head section of your CMS Index HTML file(s):

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hithismani/responsive-decap@main/dist/responsive.css"> <!-- Unminfied -->

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/hithismani/responsive-decap@main/dist/responsive.css"> <!-- Minified -->
```

## Troubleshooting

If you encounter any issues or have questions about this implementation, please feel free to [open an issue](https://github.com/hithismani/responsive-decap/issues) in this repository. I'll do my best to assist you and improve the solution.

## Contributing

I welcome contributions to enhance the mobile responsiveness or improve the implementation. If you have any improvements, bug fixes, or additional features to suggest, please submit a pull request. For major changes, kindly open an issue first to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this codebase as per the terms of the license.

## Acknowledgments

I extend my gratitude to Justin Searls for providing the initial inspiration for this project through the [gist](https://gist.github.com/searls/7fd2c3223571a58a81006e7da66bd064).