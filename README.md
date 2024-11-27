
# 50K Songs Dataset Analysis

## Overview
This repository contains a comprehensive analysis of a **50K Songs Dataset**, which includes fictional data on 50,000 songs from various genres. The dataset contains attributes like song popularity, stream count, genre, artist, album, language, and more. The analysis is conducted using **pandas**, **Matplotlib**, and **Seaborn** to uncover insights about music trends, song popularity, and correlations between different song characteristics.

## Objectives
The goal of this project is to:
- Understand the structure and characteristics of the dataset.
- Analyze trends in song popularity, stream counts, and other features.
- Investigate the distribution of songs across different genres, languages, and release dates.
- Visualize insights about how song duration, explicit content, and collaboration affect song popularity.
- Provide a deeper understanding of how various song attributes influence overall trends in the music industry.

## Dataset Description
The **50K Songs Dataset** contains the following columns:
- `song_id`: Unique identifier for the song.
- `song_title`: Title of the song.
- `artist`: Artist performing the song.
- `album`: Album where the song is featured.
- `genre`: Music genre of the song.
- `release_date`: Date the song was released.
- `duration`: Duration of the song in seconds.
- `popularity`: Popularity score of the song (1-100).
- `stream`: Total number of streams for the song.
- `language`: Language of the song.
- `explicit_content`: Whether the song contains explicit content (e.g., inappropriate language).
- `label`: Record label that published the song.
- `composer`: Composer of the song.
- `producer`: Producer of the song.
- `collaboration`: Whether the song is a collaboration with other artists.

## Project Structure
- **`analysis.ipynb`**: Jupyter notebook containing the analysis, visualizations, and insights derived from the dataset.
- **`50K_Songs_Dataset.csv`**: The CSV file containing the 50K Songs Dataset.

## Key Questions Analyzed
1. **Dataset Overview**: What does the dataset look like, and are there any missing values or anomalies?
2. **Popularity Analysis**: What are the top 10 most popular songs? What factors contribute to a song’s popularity?
3. **Genre Trends**: Which genres dominate the dataset? How does popularity vary by genre?
4. **Stream Analysis**: How does stream count correlate with song characteristics like duration and popularity?
5. **Language Trends**: How does the language of a song impact its popularity?
6. **Release Date Trends**: How has song popularity evolved over the years?
7. **Explicit Content Impact**: Do songs with explicit content tend to be more popular?

## Requirements
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For data visualization.
- **seaborn**: For advanced data visualization.

