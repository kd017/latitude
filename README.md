# Latitude - Web Visualization Dashboard

## Background

Data is more powerful when we share it with others! This project applies basic HTML and CSS to create a dashboard showing off the results of data analysis.

## Latitude - Latitude Analysis Dashboard with Attitude

The scope of ths project includes creation of a visualization dashboard website using results of analysis to study the impact of latitude on weather.

This site contains individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. There is also a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used for analysis.

### Website Content

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is built using a bootstrap table component.
    * The data is created by exporting the `.csv` file as HTML, or converting it to HTML using csv-to-html table conversion tool, e.g. [ConvertCSV](http://www.convertcsv.com/csv-to-html.htm).

The website, at the top of every page, includes a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).
