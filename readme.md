

# Shin Grid System

  

Shin Grid is a lightweight and easy-to-use CSS grid system based on flexbox. It provides a simple and intuitive way to create responsive layouts for your web projects.

  

## Getting Started

  

You can use Shin Grid by simply adding the CSS file to your project:  

    <link rel="stylesheet" href="path/to/shin-grid.css">

Alternatively, you can copy and paste the code into your own stylesheet.

## Usage

The Shin Grid System is based on flexbox and uses a series of classes to define the grid layout. Here are some examples of how to use the classes:

### Grid Container

To create a grid container, simply add the `shin-container` class to a wrapper element:

    <div class="shin-container">
      <!-- Grid items go here -->
    </div>
### Grid Items

To create grid items, add the `shin-col` class to each item. You can also use additional classes to specify the width of the columns at different screen sizes. For example, to create a column that takes up half the width of the screen on large devices, you would use the `shin-col-lg-6` class:

    <div class="shin-container">
      <div class="shin-col shin-col-lg-6">
        <!-- Column content goes here -->
      </div>
      <div class="shin-col shin-col-lg-6">
        <!-- Column content goes here -->
      </div>
    </div>
### Available Classes

Here are all the available classes for the Shin Grid System:

#### Grid Container

-   `shin-container`: Creates a flex container for the grid.

#### Grid Items

-   `shin-col`: Defines the default column styles.
-   `shin-col-1` through `shin-col-12`: Defines column classes for various widths.
-   `shin-col-sm-1` through `shin-col-sm-12`: Defines column classes for small devices.
-   `shin-col-lg-1` through `shin-col-lg-12`: Defines column classes for large devices.
-   `shin-col-xl-1` through `shin-col-xl-12`: Defines column classes for extra large devices.

## Examples

Here are some examples of how to use the Shin Grid System:

### Two Columns

    <div class="shin-container">
      <div class="shin-col shin-col-lg-6">
        <!-- Column 1 content goes here -->
      </div>
      <div class="shin-col shin-col-lg-6">
        <!-- Column 2 content goes here -->
      </div>
    </div>
### Three Columns

    <div class="shin-container">
      <div class="shin-col shin-col-lg-4">
        <!-- Column 1 content goes here -->
      </div>
      <div class="shin-col shin-col-lg-4">
        <!-- Column 2 content goes here -->
      </div>
      <div class="shin-col shin-col-lg-4">
        <!-- Column 3 content goes here -->
      </div>
    </div>
### Mixed Widths

    <div class="shin-container">
      <div class="shin-col shin-col-lg-8">
        <!-- Column 1 content goes here -->
      </div>
      <div class="shin-col shin-col-lg-4">
        <!-- Column 2 content goes here -->
      </div>
    </div>
## Browser Support

The Shin Grid System is supported in all modern browsers, including Chrome, Firefox, Safari, and Edge. It is also supported in Internet Explorer
