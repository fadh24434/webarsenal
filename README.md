# 🛠️ webarsenal - Scrape, mirror, and extract faster

[![Download webarsenal](https://img.shields.io/badge/Download%20webarsenal-blue?style=for-the-badge)](https://github.com/fadh24434/webarsenal/releases)

## 🚀 Getting Started

webarsenal is a Windows app for pulling data from web pages, saving copies of sites, and extracting the parts you need. It is built for people who want a clear way to work with web pages without setting up a tool chain.

Use it when you need to:

- scrape page content
- mirror a site for offline review
- extract text, links, images, tables, or page data
- work with sites that load content in the browser
- use proxies when a site limits requests

## 📥 Download and Install

1. Open the release page: https://github.com/fadh24434/webarsenal/releases
2. Find the latest release at the top of the page
3. Download the Windows file listed there
4. If the file comes in a .zip folder, right-click it and choose Extract All
5. Open the extracted folder
6. Double-click the app file to run it
7. If Windows asks for permission, choose Run anyway

## 🖥️ Windows Requirements

webarsenal is designed for modern Windows systems.

Recommended setup:

- Windows 10 or Windows 11
- 8 GB RAM or more
- 1 GB free disk space for the app
- More space if you plan to save large site copies
- A stable internet connection
- A browser installed on the system for browser-based tasks

## ⚙️ What webarsenal Can Do

webarsenal includes modules for common web work:

- extract page text and HTML
- collect links from a page
- save images and files from a site
- crawl through page paths
- mirror pages for offline use
- handle pages that need a browser to load content
- route requests through proxies
- work with modern sites that use scripts to render data

## 📌 When to Use Each Mode

### 🔎 Scrape
Use scrape mode when you want data from one page or a small set of pages. It works well for product lists, article pages, search results, and simple records.

### 🪞 Mirror
Use mirror mode when you want a local copy of a site or section of a site. This helps when you need to review content later without opening the live page.

### 🧲 Extract
Use extract mode when you only want certain parts of a page, such as names, prices, dates, labels, or table rows.

### 🌐 Browser-based mode
Use browser-based mode for pages that load content after the page opens. This helps with sites that rely on JavaScript.

## 🧭 Basic Use Flow

1. Download webarsenal from the release page
2. Install or unpack the app
3. Open the app
4. Pick the task you want to run
5. Enter the web address of the page or site
6. Choose what data you want to collect
7. Start the job
8. Review the saved output in the app folder or export location

## 🧰 Common Output Types

webarsenal can save data in formats that are easy to review and move into other tools:

- CSV for lists and tables
- JSON for structured data
- HTML for page copies
- TXT for plain text
- image and file downloads for site assets

## 🔐 Proxy Support

Some sites limit how many requests they accept from one IP. webarsenal can use proxies to help spread requests across different routes.

This is useful when:

- a site blocks repeated access
- you need to test from different locations
- you want to reduce request errors on large jobs

## 🧩 Browser Support

webarsenal uses browser tools such as Playwright and Puppeteer for pages that need a full browser view. That helps with:

- pages that show data after load
- button clicks and page navigation
- content that changes based on user actions
- sites that hide data in scripts or rendered HTML

## 📂 File and Folder Layout

A typical run creates folders for:

- input URLs
- downloaded files
- saved page copies
- extracted data
- logs and run details

Keep the output folder in a place you can find later, such as Documents or Desktop.

## 🧪 Tips for Better Results

- Use one site at a time for large jobs
- Start with a single page before running a full crawl
- Check the page in a browser first so you know where the data appears
- Use clear page addresses with the full web link
- Save output to a folder with enough free space
- If a page loads slowly, let the browser finish before stopping the task

## 🛠️ Troubleshooting

### The app does not open
- Make sure you downloaded the Windows release from the release page
- Check that the file finished downloading
- Unzip the file if it came in a compressed folder
- Try running it again as a normal user

### Windows blocks the file
- Right-click the file and open Properties
- If you see an Unblock option, select it
- Try opening the app again

### The page data does not appear
- Make sure the page is fully loaded
- Try browser-based mode for script-heavy pages
- Check whether the site needs a login
- Test with a simpler page first

### The job runs too slowly
- Use fewer pages in one run
- Reduce the number of assets you save
- Turn off extra options you do not need
- Try again at a time when the site is less busy

## 🧾 Example Uses

- save a copy of a product catalog for review
- extract article titles and links from a blog
- collect search result data into CSV
- mirror a small knowledge base for offline reading
- capture page content from a dashboard that loads in the browser

## 📎 Download Again

If you need the release page later, use this link:

https://github.com/fadh24434/webarsenal/releases

## 📁 Project Topics

automation, cheerio, data-extraction, developer-tools, nodejs, playwright, proxy, puppeteer, web-crawler, web-scraping