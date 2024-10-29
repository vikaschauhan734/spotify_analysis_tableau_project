# Spotify Analysis Tableau Project

This project analyzes Spotify track data by examining the distribution of popularity, the relationship between track duration and popularity, and the contribution of each artist to the total track duration.

## Project Overview

Using the Spotify dataset, this analysis provides insights into track popularity, duration trends, and artist contributions to total listening time. The project leverages calculated fields, scatter plots, and charts to visualize and interpret patterns in the data.

## Features

### 1. Popularity Distribution by Artist
   - **Objective**: Categorize tracks based on popularity and analyze distribution within each artist's portfolio.
   - **Steps**:
     - **Create a Calculated Field**: Define a new field to categorize tracks into popularity tiers (e.g., High, Medium, Low) based on their popularity scores.
     - **Visualization**: Use a stacked bar chart or treemap to show the distribution of popularity tiers for each artist.
     - **Filter for Top 10 Artists**: Limit the visualization to display only the top 10 artists with the most tracks, allowing for a focused comparison.

### 2. Popularity vs. Duration Scatter Plot
   - **Objective**: Explore the relationship between a track's duration and its popularity.
   - **Steps**:
     - **Create Scatter Plot**: Place track duration on one axis and popularity on the other.
     - **Differentiate by Artist**: Use color or size to represent different artists, providing a visual cue for analysis.
     - **Analysis Goal**: Identify any correlation between track length and popularity within the dataset.

### 3. Contribution to Total Duration
   - **Objective**: Calculate and visualize each artist’s contribution to the total track duration.
   - **Steps**:
     - **Calculate Total Duration**: Summate the duration of all tracks per artist.
     - **Pie or Donut Chart Visualization**: Display each artist's contribution to the overall track duration as a proportion of the dataset.
     - **Filter for Top 10 Artists**: Focus on the top 10 artists by total track duration to highlight major contributors.