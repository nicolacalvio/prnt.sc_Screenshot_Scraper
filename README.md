# prnt.sc_Screenshot_Scraper
Scraper of all screenshots saved in lightshot (prnt.sc)

This program scrapes the saved screenshots in prnt.sc. The images are saved in local folder output. It uses threads to execute.

Please consider scraping may be ILLEGAL.

The code is originally from https://github.com/mitchelljy/Prntsc_Scraper but i made the code run faster using threads, about half of the time, and the code was not working because of some components changed and also the urls are changed.

# USAGE
you can execute it with python3 main.py and it will run with default parameters
you can use the following arguments:  
--start_code xx1111 (2 letters and 4 numbers, default is aa1111)   
--count x (number of image to download, default is 1000)   
--output_path foldername/ (default is output/)   
