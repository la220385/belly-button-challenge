## Belly Button Biodiversity Dashboard

### Introduction
This project presents an interactive web dashboard to explore the Belly Button Biodiversity dataset, which studies microbial species—operational taxonomic units (OTUs)—that colonize human navels. The data reveals that a few microbial species are present in more than 70% of individuals, while others are more rare. This dashboard allows users to visualize the microbial community found in human belly buttons across different individuals.

### Live Dashboard
Explore the interactive dashboard [here](https://la220385.github.io/belly-button-challenge/).

### Features
- **Horizontal Bar Chart**: Displays the top 10 OTUs found in the selected individual.
- **Bubble Chart**: Visualizes the microbial species in each sample, showing the relative frequency of microbes.
- **Metadata Display**: Shows demographic information about the individual from whom the microbial data was sampled.

### Technologies Used
- **D3.js**: A JavaScript library for producing dynamic, interactive data visualizations in web browsers.
- **Plotly.js**: A graphing library that makes it easy to build visualizations.
- **Bootstrap**: For styling and positioning dashboard elements.

### Usage
Select an individual from the dropdown menu to view the diversity of microbial species in their navel. The dashboard updates the charts and displays accordingly to reflect the selected individual's data.

### Repository Structure
- `index.html`: The HTML document for the dashboard.
- `/static/js/app.js`: Contains JavaScript code for fetching and visualizing the data.
- `/static/css/style.css`: Contains styles for the dashboard.
- `/data/samples.json`: The dataset used for the visualizations.

### Resources
- [Plotly.js Documentation](https://plotly.com/javascript/)
- [D3.js Documentation](https://d3js.org/)
- [Belly Button Biodiversity Dataset](https://static.bc-edx.com/data/dl-1-2/m14/lms/starter/samples.json)

### Acknowledgments
This project utilizes the following resources:
- [GitHub Pages](https://pages.github.com/) for deployment.
- Insights and datasets provided by the [Belly Button Biodiversity study](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/).

### Conclusion
This dashboard provides a glimpse into the world of microbiomes, specifically those residing in the human navel. Through interactive visualizations, this project not only makes the scientific data accessible but also engages in exploration. It demonstrates the power of data visualization in interpreting complex datasets, making it a valuable tool for educational and research purposes.

