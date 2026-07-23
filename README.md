<div align="center">

<img src="claritylens_icon.svg" width="72" height="72" alt="ClarityLens logo" />

# ClarityLens

AI-powered image enhancer that improves brightness, sharpness, and color balance in one click.

</div>

---

## About

**ClarityLens** is a web app that uses AI to enhance image quality automatically. Upload any photo, and it adjusts brightness, sharpness, and color balance to produce a cleaner, more vibrant result — no manual editing required.

Built with React on the frontend and powered by the [PicWish](https://picwish.com) Photo Enhancer API, ClarityLens brings professional-grade photo enhancement to the browser in a single click.

## Features

- 🎨 One-click automatic enhancement — brightness, sharpness, and color correction
- ⚡ Fast processing powered by PicWish's AI models
- 🖼️ Instant before/after preview
- 📱 Clean, minimal, responsive UI

## Tech stack

| Layer | Technology |
|---|---|
| Frontend | JavaScript| React | TailwindCss
| Image enhancement | PicWish API |

## Getting started

### Prerequisites

- Node.js (v16 or later)
- A PicWish API key ([get one here](https://picwish.com/photo-enhancer-api))

### Installation

```bash
git clone https://github.com/your-username/claritylens.git
cd claritylens
npm install
```

### Environment setup

Create a `.env` file in the project root:

```
REACT_APP_PICWISH_API_KEY=your_api_key_here
```

### Run locally

```bash
npm start
```

The app will be available at `http://localhost:3000`.

## Usage

1. Upload an image from your device
2. Click **Enhance**
3. Preview the enhanced result
4. Download the improved image



## Acknowledgements

Powered by [PicWish](https://picwish.com) — Photo Enhancer API.

## License

MIT
