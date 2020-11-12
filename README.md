# James-Kelmenson-Portfolio
Portfolio of projects with links

# [Project 1: Early Universe Physics Simulation](https://github.com/kelmensonj/Newtownian-Physics-Engine)
* Coded in python, animated in blender
* Accurately simulates gravity acting on a variable number of neutrons
* Scripted and animated as a 3D rendering in Blender

# [Project 2: Market Research on Ebay Products](https://github.com/kelmensonj/UPC-s-and-the-Ebay-API-for-a-Million-Dollar-Heist)
* Integrates Ebay Shopping and Finding API's with Beautiful Soup and the Requests library in order to get supplemental data
* Collects URL's, Prices, Listing Titles, Conditions, Sellers, Seller Feedback, Seller Usernames using the Ebay API's
* Ebay API's block access to UPC's and EAN's (universal product codes), this python script uses a threadpool executor in order to make over a million URL requests per week, and scrapes URL for UPC's and EAN's
* All information is autosaved to a csv file at a variable interval. The database is built using pandas and will update whatever information is found. 
* You can update the database by querying keywords, UPC codes, sellers, etc. Anything you might type in within the Ebay.com search function can be queried.
* Built a database of well over 40,000 unique UPC codes each with data on at least 3 different listings. Successfully identified multiple underpriced Ebay listings using this information - the listings were bought and flipped for profit. 

# [Project 3: MLB Statistics, a Better Stat than Exit Velocity](https://github.com/kelmensonj/Pybaseball-Pandas-and-Python-for-DIY-Sabermetrics/blob/master/pybaseballPandasPython)
* Using pybaseball, pandas, and python, web scraped all publicly available statcast data for variable years and months and assembled all the data in a database
* Added additional data, player names, to the database which only featured unique player id's
* Cleaned and reshaped the data in order to produce park factors and indications of raw power that correlate year to year better than conventional methods 

# [Project 4: The Largest Publicly Available Study on SBMM in Videogames to Date](https://github.com/kelmensonj/COD-Warzone-SBMM-study-using-Python-BS4-Selenium-Pandas)
* Utilized Python, Beautiful Soup, Requests, Pandas, Selenium, and Multiprocessing in order to quickly and efficiently web scrape data on millions of players in the popular online Battle Royale COD Warzone
* Inspired by a similar study performed by the youtuber Xclusive Ace, where data on just a few matches and players was collected, this study collected data on over 7,000 matches and hundreds of thousands of players. 
* Used requests and multiprocessing in order to scrape html as quickly as possible. 
* A lot of the data was served using AJAX, so I used Selenium in order to scrape the data only available after Javascript rendered. 
* Used an autosaving database. You could pause and restart whenever you want. 
* (major update on the way, included my first GUI)

# [Project 5: My Youtube Channel](https://www.youtube.com/channel/UC01Ew2iYxMxFOytlZQqhOEg)
* Various product pitches and ideas
* Various shorts - animations usually around a minute in length that I made using Python scripting and Blender 3D
* Data and audio visualization videos

# [Project 6: Automating Automation]
* The project I'm most proud of, coming soon.






