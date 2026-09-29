# Circle Size Controller

This is a simple interactive HTML page that allows you to control the size of a circle using a slider.

## Features

- **Slider Control**: Adjust the radius of the circle from 10px to 200px
- **Visual Appearance**: The circle has a semi-transparent blue fill with a solid blue circumference
- **Tooltip**: Hover over the circle to see:
  - Current radius
  - Calculated area
  - Calculated circumference

## How to Use

1. Open `mistral_test.html` in any modern web browser
2. Use the slider to change the circle size
3. Hover over the circle to see the calculated values

## Technical Details

- The circle is rendered using SVG for crisp display at any size
- The fill uses RGBA color with alpha transparency (0.5)
- The stroke (circumference) uses the same color but with full opacity
- Calculations are done in real-time using JavaScript