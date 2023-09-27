# Assignment 1 - Responsive Landing Page (Tailwind)

## Project Description
This project is a responsive landing page created using HTML and styled with the Tailwind CSS framework. It includes a header section with navigation links and a call-to-action button, as well as a main content section with text and buttons. The page is designed to adapt to different screen sizes, providing an optimal viewing experience on various devices.
## UI Structure
### For larger devices
![image](https://github.com/saifulislam05/tailwind-lp-ass-1/assets/73392705/4ccfde51-d705-4a03-aa07-b9ef3d696285)

### For medium devices
![image](https://github.com/saifulislam05/tailwind-lp-ass-1/assets/73392705/e266c327-3392-425e-b2c6-509d8ae1bbfe)

### For small devices
![image](https://github.com/saifulislam05/tailwind-lp-ass-1/assets/73392705/5e69e93d-21f3-4a0d-b70a-fe5d87c6d4be)

## Code Explanation
### Header Section

#### `<body class="text-gray-600">`
- Sets the text color of the entire page to gray.

#### `<header>`
- Defines the header section of the webpage.

#### `<div class="container flex flex-col flex-wrap items-center p-5 mx-auto md:flex-row">`
- A container that centers its content both vertically and horizontally.
- Uses flexbox for layout.
- Adds padding to the content.
- Adjusts the layout for medium-sized screens and above.


#### `<a class="flex items-center mb-4 font-medium text-gray-900 cursor-pointer md:mb-0">`
- Creates a link with:
  - A flex layout.
  - Vertical alignment of items.
  - Margin at the bottom.
  - Font weight set to medium.
  - Text color set to gray.
- For medium-sized screens and above, it removes the margin at the bottom.

#### `<svg class="w-10 h-10 text-white p-2 bg-green-500 rounded-full" ...>`
- An SVG image with specific styles, including:
  - Size
  - Padding
  - Background color
  - Rounded corners

#### `<span class="ml-3 text-xl">Geekster</span>`
- Adds margin to the left of the text.
- Sets the text size to extra-large.

Inside the navigation:

#### `<nav class="flex flex-wrap items-center justify-center md:mr-auto md:ml-4 md:pl-4 md:border-l md:border-gray-500">`
- Creates a navigation menu with:
  - Flex layout
  - Vertical and horizontal alignment of items
- For medium-sized screens and above, it:
  - Adds margin to the right
  - Adds margin to the left
  - Adds a left border
  - Sets the border color to gray

#### `<a href="" class="mr-5 hover:text-gray-900">`
- Creates a navigation link with:
  - Margin to the right
  - A hover effect that changes the text color to gray

#### `<button class="flex items-center px-3 py-1 mt-4 bg-gray-100 rounded hover:bg-gray-200 md:mt-0">`
- Creates a button with:
  - Flex layout
  - Vertical alignment of items
  - Padding both horizontally and vertically
  - Margin at the top
  - Background color set to gray
  - Rounded corners
- For medium-sized screens and above, it removes the margin at the top.

### Main Content Section

#### `<main>`
- Defines a main section of the webpage.

#### `<div class="container flex flex-col items-center px-5 py-24 mx-auto text-center md:flex-row">`
- A container that centers its content both vertically and horizontally.
- Uses flexbox for layout.
- Adds padding to the content.
- Adjusts the layout for medium-sized screens and above.

Inside the left column:

#### `<div class="flex flex-col items-center mb-16 lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 md:items-start md:text-left md:mb-0">`
- A flex container with:
  - Column layout
  - Vertical alignment of items
  - Horizontal centering
- For medium-sized screens and above, it:
  - Grows to fill available space
  - Adds padding on the right
  - Aligns items to the start

#### `<h1 class="mb-4 text-3xl font-medium text-gray-900 sm:text-4xl">`
- Adds margin at the bottom
- Sets the text size to 3xl
- Sets font weight to medium
- Sets text color to gray
- For small screens and above, it increases the text size to 4xl.

#### `<p class="mb-8 leading-relaxed">`
- Adds margin at the bottom
- Sets line height to relaxed

Inside the button group:

#### `<button class="px-6 py-2 text-lg text-white bg-green-500 rounded hover:bg-indigo-600 mr-4">`
- Creates a button with:
  - Padding
  - Text size
  - White text color
  - Green background color
  - Rounded corners
  - On hover, it changes the background color to indigo.

#### `<button class="px-6 py-2 ml-4 text-lg text-gray-700 bg-gray-100 rounded hover:bg-gray-200">`
- Creates another button with:
  - Padding
  - Text size
  - Gray text color
  - Gray background color
  - Rounded corners
  - On hover, it changes the background color to a lighter gray.

Inside the right column:

#### `<div class="w-5/6 lg:max-w-lg lg:w-full md:w-1/2">`
- Sets the width of the div for different screen sizes.

#### `<img class="object-cover object-center rounded" alt="hero" src="...">`
- Adds styles to the image, including:
  - Covering its container while maintaining the aspect ratio
  - Rounding the corners.

