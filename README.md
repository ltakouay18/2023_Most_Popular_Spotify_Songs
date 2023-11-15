# 2023_Most_Popular_Spotify_Songs
This Exploratory Data Science Project aims to investigate trends and patterns in the most streamed songs of 2023 on Spotify.

### Objective and Scope
* Collect, clean and analyze the spotify dataset from Kaggle: [2023_Spotify_Songs](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023)
* Determine variables that contribute to song popularity
* Visualize data to show relationships between variables
* Share findings and insights to help make data-driven business decisions

### Data Description
* track_name: Name of the song
* artist(s)_name: Name of the artist(s) of the song
* artist_count: Number of artists contributing to the song
* released_year: Year when the song was released
* released_month: Month when the song was released
* released_day: Day of the month when the song was released
* in_spotify_playlists: Number of Spotify playlists the song is included in
* in_spotify_charts: Presence and rank of the song on Spotify charts
* streams: Total number of streams on Spotify
* in_apple_playlists: Number of Apple Music playlists the song is included in
* in_apple_charts: Presence and rank of the song on Apple Music charts
* in_deezer_playlists: Number of Deezer playlists the song is included in
* in_deezer_charts: Presence and rank of the song on Deezer charts
* in_shazam_charts: Presence and rank of the song on Shazam charts
* bpm: Beats per minute, a measure of song tempo
* key: Key of the song
* mode: Mode of the song (major or minor)
* danceability_%: Percentage indicating how suitable the song is for dancing
* valence_%: Positivity of the song's musical content
* energy_%: Perceived energy level of the song
* acousticness_%: Amount of acoustic sound in the song
* instrumentalness_%: Amount of instrumental content in the song
* liveness_%: Presence of live performance elements
* speechiness_%: Amount of spoken words in the song
* Potential Use Cases:
* Music analysis: Explore patterns in audio features to understand trends and preferences in popular songs.
* Platform comparison: Compare the song's popularity across different music platforms.
* Artist impact: Analyze how artist involvement and attributes relate to a song's success.
* Temporal trends: Identify any shifts in music attributes and preferences over time.
* Cross-platform presence: Investigate how songs perform across different streaming services.

### Key Findings
​
*********
- The most popular Artist was the Weeknd, and he is also the artist for the most popular song 'Blinding lights'. 
'Blinding Lights' was released in 2019, but still maintained a large number of streams.\
- The top 10 most streamed songs from spotify, ranking did not coincide with number of streams. It could also be an indicator that a songs has been on the charts for a longer period.
- There was no strong correlation between numerical factors and the number of streams, however there were medium correlations between factors.
- The majority of songs in the dataset had danceability, valence and energy around 60%. 
- The majority of songs have approximately 120 bpm.
- Songs with the largest streams had a key of C#.
