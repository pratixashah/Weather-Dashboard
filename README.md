# Web-Design
 
A visualization dashboard website using visualizations plotting weather data. This dashboard creates individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. A landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

## Data/Image Sources(Assets dir):
- This dir contains Images used for visualizations 
- cities.csv file as Data Source 
- Data.html file contains data from cities.csv in html format

## Resources(style.css):
- style.css contains classes of styles used for styling the this website content.
- It includes @media query as well.

## Visualizations Analysis(visualizations dir)
- It contains html pages of Visualizations Analysis for Latitude vs - Max Temp, Humidity, Cloudiness, Wind Speed

## This website, 
- Uses a Bootstrap theme
- Uses meaningful glyphicons next to links in the header
- Contains active page link highlighted and disabled for the same page in the header (Except Home Page link named "Latitude" - All time Accessible)
- Has visualization navigation on every visualizations page with an active state

  ## A landing page containing(index.html):
    - An explanation of the project.
    - Links to each visualizations page. A sidebar containing preview images of each plot, and clicking an image will take the user to that visualization.
    
  ## Four visualization pages(in visualizations dir),
    each with:
    - A descriptive title and heading tag.
    - The plot/visualization itself for the selected comparison.
    - A description of the plot and its significance.
    
  ## A “Comparison” page(comparison.html):
    - Contains all of the visualizations on the same page so we can easily visually compare them.
    - Uses a Bootstrap grid for the visualizations.
    - The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
    
  ## A “Data” page(in Assets dir Data.html):
    - Displays a responsive table containing the cities data used in the visualizations.
    - The table is a bootstrap table component.

The website, at the top of every page, have a navigation menu that:
  - Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
  - Contains a dropdown menu on the right of the navbar named “Plots” that provides a link to each individual visualization page.
  - Provides two more text links on the right: “Comparison,” which links to the comparison page, and “Data,” which links to the data page.
  - Is responsive (using media queries). 
 
