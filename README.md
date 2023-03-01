# Movie-Project

In 2019, I decided to copy my DVDs to harddisk so I can access them directly with my mediacenter when ever I want, without replacing the discs. Furthermore, I wanted to have some statistics, about the movie files and the movie titles.

The movie file information were collected on my Linux based NAS with the command mediainfo. The following command was used to generate the mediainfo.txt file which will be used during this project:

    $ find . -name "*.m4v" | sort | while read m; do mediainfo "${m}" >> ~/mediainfo.txt; done

Additionally I am using OMDb API (https://www.omdbapi.com/) to collect more data on my movies.

And yes I know, I have a weird taste in movies :)
