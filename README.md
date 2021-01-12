# Scraping a small videogame dataset from Wikipedia
## What I'm pulling
Data comes from these pages,

- https://en.wikipedia.org/wiki/List_of_best-selling_PC_games
- https://en.wikipedia.org/wiki/List_of_most-played_video_games_by_player_count

Where the format is slightly different, but some games may appear on both lists. The total size of the data is only a few hundred rows (at the time of writing) but I found that it was a great place to start working with [BeautifulSoup4](https://www.crummy.com/software/BeautifulSoup/) for web scraping.

## Notebook and (really simple EDA)
I also used this repository to test using [Jupyter Notebooks](https://jupyter.org/) in a virtualenv and with managed dependencies through [Poetry](https://python-poetry.org/).

To run the notebook, use the venv created by ```poetry install``` or run ```poetry run jupyter notebook``` to start a Jupyter Lab server in this repository.