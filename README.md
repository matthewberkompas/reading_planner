# Reading App:
This is a web or mobile app which takes a book and a date range and calculates how many chapters/pages you would need to read each day to finish it in that time frame.

### Basic Specs:
- It takes a book,
  - Name
  - Author?
  - Number of chapters
  - Number of pages (not including table of contents,  index, author bio etc.)
  - Date range (start date and finish date)
  - Divide the number of chapters (or pages) by the number of days to calculate how many pages someone would need to read each day to finish in that time frame.

### Advanced Specs:
- ...basic features
- Connect it all to a real calendar and save the reading plan for each book a user enters so that they could see where they should be at.
- Add the ability to set a reminder to read each day (this reminder would be set on the book itself).

  - List View:
    A list view would be provided of all the books a user has entered in the app with three different sections/statuses:
    - Read,
    - Reading and
    - Future Reading
    - Checking the book (swiping right on mobile) would complete it and move it to the “Read” section/status of the list.
    - The “Reading” section of the list would be automatically populated by books that are supposed be be in progress based on that book’s start date (If the start date for “Aesop’s Fables” was Jan. 1st and today is Jan. 5th, that book would be put under Reading).
    - Clicking/tapping on a book in the list would bring up info about it:
      - Name
      - Author?
      - Number of pages
      - Number of Chapters
      - Status (Read, Reading, or Future Reading)
      - Where you are supposed to be in the book right now
      - The start date
      - The finish date

	- Reporting:
    Note: These stats are only accurate as far as the user is accurate about what they actually read.
    - Provide monthly and annual reports on the following stats:
      - Number of books read (determined by whether a book was checked off or not)
      - Number of pages read (the collective number of pages of a user’s books in the app)
      - Maybe provide weekly reports with the number of books in progress…

### Long-term Future Spec:
- Connect the app to a huge library API containing virtually every, single book with info about it.
  - Name,
  - Author,
  - Number of pages and
  - Number of Chapters
- This would allow users to enter the ISBN number or title to find a book instead of entering all the above information manually. If the book couldn’t be found in the API, you could provide a manual entry option anyways.
