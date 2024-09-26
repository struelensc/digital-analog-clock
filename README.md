# Digital Analog Clock

## Overview

This project is a **Digital Analog Clock** built using HTML, CSS, and JavaScript. The clock visually simulates the classic analog style with moving hour, minute, and second hands. Each hand rotates according to the current time.

## Features

- **Analog Clock Design**: Displays current time with hour, minute, and second hands.
- **Smooth Animation**: The clock hands transition smoothly to mimic the continuous movement of a real analog clock.
- **JavaScript for Time**: Uses JavaScript to update the clock every second.

![Photo of Digital Analog Clock application](photo-sample.png)

## File Structure

- **HTML**: Defines the structure of the clock and hands.
- **CSS**: Styles the clock, hands, and background.
- **JavaScript**: Handles time updates and hand rotations.

## How It Works

1. **HTML Structure**:

   - The clock face contains three div elements representing the hour, minute, and second hands.

2. **CSS**:

   - The `.clock` class styles the clock's frame and circular shape.
   - The `.hand` class styles the clock hands, including their width, height, and positioning.
   - The selectors `.hour-hand`, `.minute-hand`, and `.second-hand` are used query selection in JavaScript and enable the smooth transitions for the hand movements.

3. **JavaScript**:
   - The `setDate()` function is executed every second using `setInterval()`.
   - This function:
     - Retrieves the current time using `Date()`.
     - Calculates the appropriate degrees of rotation for the second, minute, and hour hands.
     - Updates the CSS `transform` property of each hand to visually rotate them on the clock.

## Technologies Used

- **HTML5**: For structuring the clock interface.
- **CSS3**: For styling the clock and hands.
- **JavaScript**: For retrieving the current time and animating the clock hands.

## Usage

Open the `index.html` file in any modern browser, and the clock will start running, showing the current time.

## License

This project is open-source and free to use.
