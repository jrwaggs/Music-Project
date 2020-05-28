# Music-Project
Exploring graph-based techniques for music recommendation.  

## What's in the repo:

### Data files
* 10k_spotify_rankings.csv - Spotify stream count for the top 10k artists.
* playlist_graph_artists_scores.csv 
* artist-yahoo-ratings.csv - Yahoo! artist ratings data.
* artist_dictionary.data  - Core artist dictionary.
* filtered_tags_dict.data - User-tag dictionary filtered to the most common genres.
* tags_dict.data - Core user-tag dictionary.

### Notebooks
* Initial Resulys.ipynb  - Our initial look into the accuracy of graphs against various Spotify playlists.
* Evaluation.ipynb - Evaluating the impact of graph structure on average novelty score.
* Popularity Distribution.ipynb - Evaluating the Yahoo! rating & Spotify popularity distributions of ghraphs and playlists.
* Network Graph - The first notebook that was created at the start of the project. For reference only.

### /music_graph
* All of the core graph-building code written for the project.  Code has been packaged to make importing the necessary functions and data cleaner, consistent, and more efficient across multiple experimenting and evaluation notebooks.
