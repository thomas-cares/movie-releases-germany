# movie-releases-germany

### what's happening
scraping for upcoming theatrical film releases in Germany, 
creating a clean data frame containing:
- release date
- film title
- director
- actors
- countries of production
- year of production
- distribution company in Germany
- link to film still (2560x1440px)

### added services:
- youtube trailer: searching youtube for the respective movie trailer by keywords returning youtube-link
- lets you choose how many upcoming weeks you want to scrape for releases
- exports an excel and csv file
- rings a bell when script is finished as it may take a couple of minutes before the scraping is done
- option to auto attach the exported excel to an email and send it

### please note:
the script searches youtube by film title, director name, name of distribution company and the word 'trailer'.
The script is then returning the top youtube search hit to the column 'trailer' assuming it is very likely the movie's respective trailer.
Unfortunately this does not necessarily hold true.
So please be cautious relying on the "trailer"-column.

### files
jupyter notebook: 
running all cells you will be asked how many upcoming weeks you want to scrape

### folder exported_files:
here you'll find an example excel and csv file giving you an idea how the export looks like.
also the jupyter notebook python code is set up to create a folder 'exported_files' to drop the resulting excel and csv with datestamp there.
