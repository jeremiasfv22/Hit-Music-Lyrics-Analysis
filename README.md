# Hit-Music-Lyrics-Analysis

This passion project is an extension of the US Streaming Hits w/ Spotify Data project: https://github.com/jeremiasfv22/USA-Hits-Spotify-Data-Project. While the previous project analyzed the musical qualities of a song that entered the top 50 on streaming in the USA since March 2017, **this project analyzes the lyrical qualities of hit songs** that not only entered the top 50 on streaming but stayed there for enough weeks to **earn at least 72.5 million streams during their time on the top 50**.

If we take the top 100 songs per year (measured by how much streams it got during its time in the top 50 on HITS Magazine's Streaming chart) we see that the cutoff for the top 100 is around 72.5 million streams (using 2018-2021 data). 

Since 2017, I collected data from the HITS Daily Double Magazine on this Google Sheet: https://docs.google.com/spreadsheets/d/165OdLYjLt4AgeqP5S5PunRonDkpp28nueHLFv994bPk/edit?usp=sharing

This project utilizes various Python packages, such as gspread to connect Python with Google Sheets and Genius's API which hosts lyrics. 

The following Notebook collects songs from the Google Sheets above and looks for each song's respective lyrics. 
