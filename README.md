# Basic Website Package

A lightweight and responsive website template packaged as an npm module. This package includes a basic HTML structure, responsive CSS, and JavaScript for creating a simple website.

## Features

- **Responsive Design**: Built to adapt to different screen sizes using CSS media queries.
- **Clean Structure**: Organized folder structure with HTML, CSS, and JavaScript files.
- **Customizable**: Easily extendable to meet your project needs.

---

## Installation

To use this package, you need Node.js and npm installed. Install the package using:

```bash
npm install leno.html
```

---

## Usage

After installing, you can find the website template in the dist folder. Copy the contents of the folder and use them in your project.

Alternatively, you can use it directly in your project:

- Add the HTML to your project:

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./node_modules/leno.html/dist/style.css">
  <title>My Website</title>
</head>
<body>
  <script src="./node_modules/leno.html/dist/script.js"></script>
</body>
</html>
```

- Customize the files as needed.

## File Structure

```bash
leno.html/
├── dist/
│   ├── index.html     # Responsive HTML file
│   ├── style.css      # Minified CSS for responsiveness
│   └── script.js      # Basic JavaScript logic
├── src/
│   ├── styles/        # Source CSS files (optional for custom build)
│   ├── js/            # Source JavaScript files
├── package.json       # npm package configuration
├── README.md          # Documentation
```

---

## Development

### To modify or rebuild the files:

- Clone the repository:

```bash
git clone https://github.com/lenojoseph/leno.html.git
cd leno.html
```

- Install dependencies:

```bash
npm install
```

- Build the CSS:

```bash
npm run build
```

---

## License

This package is proprietary software. All rights reserved. Unauthorized copying, distribution, or modification is prohibited without prior permission.

## Contributions

We welcome contributions! Whether it's fixing bugs, adding features, or improving documentation, feel free to open a pull request or issue.

---

## Support

If you find this package useful, please give it a star ⭐ on GitHub! Your support helps keep the project alive and thriving.

---

## Contact Details

- [Discord Server](https://discord.gg/PNpVAp2vwP)
- [Our Site](https://lenobot.xyz)
- [Developer e-Mail](mailto:developer@lenobot.xyz)
- [Email Me](mailto:support@lenobot.xyz)