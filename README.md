# Color Converter

A simple JavaScript library for converting colors between different formats: HEX, RGB, and HSL.

## Installation

```bash
npm install color-converter-js
```

## Usage

```javascript
const ColorConverter = require('color-converter-js');

// Convert HEX to RGB
const rgb = ColorConverter.hexToRgb('#ff0000');
console.log(rgb); // Output: [255, 0, 0]

// Convert RGB to HEX
const hex = ColorConverter.rgbToHex(255, 0, 0);
console.log(hex); // Output: #ff0000

// Convert HEX to HSL
const hsl = ColorConverter.hexToHsl('#ff0000');
console.log(hsl); // Output: [0, 1, 0.5]

// Convert RGB to HSL
const hsl2 = ColorConverter.rgbToHsl(255, 0, 0);
console.log(hsl2); // Output: [0, 1, 0.5]

// Convert HSL to RGB
const rgb2 = ColorConverter.hslToRgb(0, 1, 0.5);
console.log(rgb2); // Output: [255, 0, 0]

// Convert HSL to HEX
const hex2 = ColorConverter.hslToHex(0, 1, 0.5);
console.log(hex2); // Output: #ff0000
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
