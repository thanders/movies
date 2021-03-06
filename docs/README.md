# Requirements

1.  A Bourne Again Shell (BASH) terminal emulator (e.g. Gnome Terminal)
2.  W3.org's html-xml-utils \- These can be installed by typing ``` apt install html-xml-utils ``` in your terminal emulator
3.  The movie.sh and process_movies.sh files

# How to run the script
1.  Download the both scripts from Github. Keep them in the same directory.
2.  Open the terminal emulator
3.  Change Directory (CD) into the directory that contains the movie.sh shell script
4.  Permission both scripts to be run by typing ``` CHMOD u+x movie.sh ``` and ``` CHMOD u+x process_movies.sh ```
5.  Execute the script ``` ./movie.sh ```

# Tools and techniques used
The following bash tools and techniques are used for text processing:
  - Wget \- Retrieves web pages or files via HTTP, HTTPS or FTP
  - Grep \- Searches files for lines that match a given pattern
  - Sed \- A stream editor that is used to perform basic text transformations such as, selecting text between two patterns.
  - Hxnormalize \- Part of the html-xml-utils package. Used for normalizing HTML.
  - Hxselect \- Part of the html-xml-utils package. Used for selecting selecting specific HTML tags.
  - IFS \- Internal field separator
  - Redirecting
      - Pipes \- Used to redirect the output from one command as input for another or 
      - File redirects

# Works Cited
https://www.ss64.com/bash

https://www.w3.org/Tools/HTML-XML-utils/

http://www.imdb.com/
