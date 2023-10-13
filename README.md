# Line Chart with Filtering and Date Range Selection

This is a web-based line chart application that allows you to visualize and interact with data. The line chart displays time-series data for various endpoints, with options for special endpoint filtering and date range selection. 

## Features

1. **Line Chart Visualization:** The application displays data as a line chart, where the x-axis represents time, and the y-axis represents the number of requests. Each line on the chart corresponds to a different endpoint

2. **Special Endpoint Filtering:** You can filter the data to display only special endpoints by clicking the "Filter Special Endpoints" button. 

## Design Choices

**Chart Library:** We used the Chart.js library for creating interactive and visually appealing line charts, simplifying the development process

**Date Formatting:** We employed the `date-fns` and `moment.js` libraries to handle date formatting, making it easier to parse and manipulate date values

**Date Range Picker:** The `daterangepicker` library was integrated to allow users to select date ranges conveniently. The date range picker also supports specifying the date format.

**Special Endpoint Filtering:** Data filtering is implemented by checking the `special` property of each data point. Clicking the "Filter Special Endpoints" button updates the chart with special endpoints only.

**Reset Feature:** The "Reset Chart" button allows users to revert to the original chart with the complete dataset.

## How to Use

1. **Filter Special Endpoints:** Click the "Filter Special Endpoints" button to view special endpoints only.

2. **Select Date Range:** Use the date range picker to select a custom date range and update the chart. If the selected date range does not contain any data, the system triggers an alert to inform the user, and the line graph is cleared.
3. **Reset Chart:** Click the "Reset Chart" button to revert to the original chart with the complete dataset.

## Development

You can further customize and extend this application by modifying the JavaScript code and styles. Explore the HTML structure to adapt it to your needs.

Feel free to reach out if you have any questions or need assistance with this chart application.

email: vatsalp.edu@gmail.com

