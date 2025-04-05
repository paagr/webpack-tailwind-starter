# webpack-tailwind-starter

A lightweight frontend development starter with webpack and Tailwind CSS integration. Provides a pre-configured environment for building modern web applications with hot reloading, CSS processing, and utility-first styling.

## Features

- 🚀 Webpack 5 bundling
- 💨 Tailwind CSS v4 integration
- 🔄 Hot module replacement
- 📱 Responsive design ready
- 🎨 PostCSS processing

## Prerequisites

- Node.js (v18 or higher)
- npm (v10 or higher)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/paagr/webpack-tailwind-starter.git
cd webpack-tailwind-starter
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm start
```

This will start the development server and open your browser at `http://localhost:8080`.

### Build for production

```bash
npm run build
```

Production files will be generated in the `dist` directory.

## Project Structure

```
webpack-tailwind-starter/
├── src/
│   ├── index.html     # HTML template
│   ├── index.js       # JavaScript entry point
│   └── styles.css     # Main stylesheet with Tailwind imports
├── .gitignore
├── package.json
├── package-lock.json
├── postcss.config.mjs # PostCSS configuration
├── webpack.config.js  # Webpack configuration
└── README.md
```

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request
