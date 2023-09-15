# D3 Scatterplot Project

This is a simple D3.js scatterplot project that displays cyclist data with and without doping allegations. The chart visualizes the relationship between the year of the race and the time taken by the cyclists.

## How to Use

1. Clone this repository or download the HTML file.
2. Open the HTML file in a web browser.

## Project Description

This project uses D3.js to create an interactive scatterplot chart. The chart includes the following elements:

- X-axis: Represents the years of the races.
- Y-axis: Represents the time taken by the cyclists.
- Circles: Each circle on the chart represents a cyclist. Circles are color-coded as follows:
  - Red circles: Cyclists with doping allegations.
  - Green circles: Cyclists with no doping allegations.
- Tooltip: Hover over a circle to see detailed information about the cyclist, including their name, nationality, year of the race, time taken, and doping allegations (if any).

## Data Source

The data used for this project is fetched from [https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json](https://raw.githubusercontent.com/freeCodeCamp/ProjectReferenceData/master/cyclist-data.json). It includes information about various cyclists and their race performance.

## Dependencies

This project uses D3.js version 7, which is loaded from [https://d3js.org/d3.v7.min.js](https://d3js.org/d3.v7.min.js).

## Styling

The chart and its elements are styled using CSS to improve its appearance and readability.

## Notes

- You can interact with the chart by hovering over the data points to view additional information.
- The legend on the chart explains the color-coding of the circles.

Feel free to explore the scatterplot and analyze the cyclist data visually!
