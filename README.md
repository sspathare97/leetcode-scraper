# LeetCode Scraper

Scrapes Problems, Companies, Company Problems, Interviews, Interview Problems from LeetCode.

## Download LeetCode Scraped Data
Download LeetCode Scraped Data as of September 6, 2020 20:45:00 IST:
* [Explore Scraped-Data Directory](https://github.com/sspathare97/leetcode-scraper/tree/master/Scraped-Data)  
* [Download Scraped-Data.zip](https://raw.githubusercontent.com/sspathare97/leetcode-scraper/master/Scraped-Data.zip)  

Company Problems are stored in both name-wise and period-wise directory structures for convenience.

## Scraped Data Columns
* Problems- Id, Title, Acceptance, Difficulty, Frequency, Link
* Companies- Serial, Name, Count, Link
* Company Problems- Id, Title, Tags, Acceptance, Difficulty, Frequency, Link
* Interviews- Serial, Title, Chapters, Problems, Link
* Interview Problems- ChapterSerial, Chapter, ProblemSerial, Problem, Id, Acceptance, Difficulty, Frequency, Link

## Directory Structure
```
.
├── Problems-*.csv
├── Companies-*.csv
├── Interviews-*.csv
├── Interview_Problems
│   ├── Amazon-*.csv
│   ├── Apple-*.csv
│   ├── ...
├── Company_Problems
│   ├── Name-wise
│   │   ├── Amazon
│   │   │   ├── Amazon-6_months-*.csv
│   │   │   ├── Amazon-1_year-*.csv
│   │   │   ├── Amazon-2_years-*.csv
│   │   │   └── Amazon-All_time-*.csv
│   │   ├── Apple
│   │   │   ├── Apple-6_months-*.csv
│   │   │   ├── Apple-1_year-*.csv
│   │   │   ├── Apple-2_years-*.csv
│   │   │   └── Apple-All_time-*.csv
│   │   ├── ...
│   └── Period-wise
│       ├── 6_months
│       │   ├── Amazon-6_months-*.csv
│       │   ├── Apple-6_months-*.csv
│       │   ├── ...
│       ├── 1_year
│       │   ├── Amazon-1_year-*.csv
│       │   ├── Apple-1_year-*.csv
│       │   ├── ...
│       ├── 2_years
│       │   ├── Amazon-2_years-*.csv
│       │   ├── Apple-2_years-*.csv
│       │   ├── ...
│       ├── All_time
│       │   ├── Amazon-All_time-*.csv
│       │   ├── Apple-All_time-*.csv
│       │   ├── ...
```

## Environment Setup
Create an .env file and add the following environment variables (refer .env.example).
```javascript
LEETCODE_USERNAME = 
LEETCODE_PASSWORD = 
```

## Usage
Simply run all the cells.