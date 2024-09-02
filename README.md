# go-unit-converter

https://roadmap.sh/projects/unit-converter

## Requirements

Build a simple web page that will have different sections for different units of measurement. The user can input a value to convert, select the units to convert from and to, and view the converted value.

- The user can input a value to convert.
- The user can select the units to convert from and to.
- The user can view the converted value.
- The user can convert between different units of measurement like length, weight, temperature, etc (more given below).
- You can include the following units of measurement to convert between:

- Length: millimeter, centimeter, meter, kilometer, inch, foot, yard, mile.
- Weight: milligram, gram, kilogram, ounce, pound.
- Temperature: Celsius, Fahrenheit, Kelvin.

## How it works

You don’t need to use any database for this project. There will be a simple webpage that will submit the form to the server and get the converted value back and display it on the webpage.

You can have 3 webpages for each type of unit conversion (length, weight, temperature) with forms to input the value and select the units to convert from and to. Submitting a form will submit the data to the current page (i.e. `target="_self"`) and display the converted value. You can do this using the backend programming language of your choice i.e. check if the form is submitted and then calculate the converted value and display it on the webpage, if not submitted then display the form.
