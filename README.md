# FinSwift
Efficient, parallelized data format-compatible analysis and valuation software for equities in Python leveraging the yFinance API for recent stock data. 2020 Grinspoon Entrepreneurial Concept Prize winner. 

Written in Python3, FinSwift started as a quarantine boredom/passion project of mine. 
One of my hobbies is Graham and Dodd-inspired fundamental financial analysis and value investing. It's often a rather meticulous process and involves hours upon hours of scrutinizing annual reports and financial statements by hand.
After a few days too many of burning out my eyeballs by staring at balance sheets all day, I decided to figure out a way I could expedite and streamline the process by applying my knowledge of programming.

In the end was born FinSwift, a program that supports valuation-based screening on individual stocks or lists of equities that are part of data files. 
Instead of me having to use a clunky, freemium screener from somewhere online, I now had my own in-house software that could perform a rapid discounted cash flow valuation, assess solvency, and analyze price and assets without needing to bust open an Excel spreadsheet or a 10-K report.

I picked Python3 as the language because:
1. It's true that C++ runs more efficiently than Python, but I didn't need real-time speed so long as processing time didn't take too long
2. Lots of prebuilt APIs in Python - very convenient
3. Python generally involves many fewer headaches when implementing algorithms with lists and sets of data (parallel techniques improved runtime speed by 230%)
I also used the free yFinance (Yahoo Finance) API on this project in order to have a source from which to pull stock data and financials that I used to compute calculations on. There are many other, more robust alternatives for API, but unfortunately many charge high yearly rates that would be unsustainable for this project.

Ultimately, FinSwift won the 2020 Grinspoon Entrepreneurial Concept Prize. Looking forward to developing and expanding on this project.

Credit:
Ranaroussi for developing the original yfinance API
Rodrigobercini for fixing and updating the yfinance API that is used in this project

