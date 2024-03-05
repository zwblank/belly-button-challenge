# Belly-Button-Challenge

In this challenge, I built an interactive dashboard to explore a dataset of belly button biodiversity that reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.


# Visualizations

Using the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json, I created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in an individual, a bubble chart that displays each sample, and the individual's demographic information. All


## Horizontal Bar Char

The horizontal bar chart uses the following label values:
    sample_values as the values for the bar chart.

    otu_ids as the labels for the bar chart.

    otu_labels as the hovertext for the chart.


## Bubble Chart

    otu_ids for the x values.

    sample_values for the y values.

    sample_values for the marker size.

    otu_ids for the marker colors.

    otu_labels for the text values.


## Demographic Information

    displays the key value pair from the metadata JSON object.

    sample_values for the y values.

    sample_values for the marker size.

    otu_ids for the marker colors.

    otu_labels for the text values.
