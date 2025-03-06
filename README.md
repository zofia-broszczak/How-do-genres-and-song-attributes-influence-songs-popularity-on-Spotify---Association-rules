## How do genres and song attributes influence songs' popularity on Spotify?

Zofia Broszczak, 446277, USL, DS&BA UW

**Overview**

Music streaming platforms like Spotify collect a huge amount of data about songs and listener behavior. Understanding what makes a song popular is important for artists, producers, and streaming platforms to connect better with their audiences. Popularity reflects how much a song is liked and listened to, and it can be influenced by many factors, including the song's features.

This study uses association rule mining to find patterns between song attributes and their impact on popularity.

**Dataset Information**

The dataset utilized for this project was sourced from Kaggle ([Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset?resource=download)). While Spotify previously provided its own datasets for researchers, access to these has since been discontinued. Although Spotify’s API still is a viable option for obtaining accurate data, I have opted not to use it, as doing so falls outside the scope of this project.

The chosen Kaggle dataset is comprehensive and includes essential features like danceability, energy, and popularity. Alomng the dataset, there are well-documented variable descriptions, making it accessible and easy to interpret. Additionally, it has been widely used by researchers, which further validates its reliability. These factors make it a great choice for my project.

**Key findings**

This reasearch paper explored how song attributes and genres influence popularity on Spotify using association rule mining. Genres like dance, rock, and house are strong indicators of high popularity, while others such as sleep, chill, and indian are linked to medium popularity, and niche genres like black-metal and grindcore are strongly associated with low popularity. Removing genre as a factor revealed additional patterns: highly popular songs tend to have a medium length, explicit content, high danceability, a minor key, and moderate tempo, while medium-popularity songs are moderately energetic, minimally acoustic, and fast-paced. Conversely, low-popularity songs are characterized by short durations, low danceability, loudness, and moderate tempo. These findings highlight the nuanced role of both musical features and genres in determining a song’s popularity, offering valuable insights for artists, producers, and streaming platforms seeking to optimize audience engagement.
