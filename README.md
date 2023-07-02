<div align="center">
  <a href="https://shallvhack.github.io"><img src="https://camo.githubusercontent.com/c0dca71e8f9333fa3870ebe0149ea7fd6ca4d27c02504cbef02af1ecf50fc0e2/68747470733a2f2f7062732e7477696d672e636f6d2f70726f66696c655f62616e6e6572732f333232343030363932382f313631313038353130332f3135303078353030" /></a>
  <h1>🌟 The Hacker News Scraper 🌟</h1>
   <p>👩‍💻 Author: <a href="https://github.com/mymadhavyadav07">Madhav 👩‍💻</a></p>
</div>


## 📋 Overview
This tool is a powerful web scraping application designed to scrape the latest news articles from [The Hacker News](https://thehackernews.com/) website and deliver them to a designated Discord channel. Stay up-to-date with the latest cybersecurity news effortlessly!😉


## ✨ Features

- Scrapes [The Hacker News](https://thehackernews.com/) for the latest articles
- Extracts relevant information such as article title, image, publication date and description
- Sends formatted article notifications to a Discord channel
- Customizable scraping intervals to suit your needs
- Simple setup and configuration

## 🔧 Prerequisites

- Python 3.10 or above
- pip package manager
- Discord Bot token and channel ID

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/mymadhavyadav07/The-Hacker-News-Scraper.git
2. Install dependencies:
   ```bash
   cd The-Hacker-News-Scraper
   python3 -m pip install -r requirements.txt


## 📚 Usage

```bash
python3 main.py -h

usage: main.py [-t TOKEN] [-c CHANNEL_ID] [-h]

options:
  -h, --help            show this help message and exit
  -c, --channel-id      Discord Channel ID
  -t, --token           Discord bot token
  -s, --interval        Scraping interval in seconds
```

## ⚙️ Configuration
You can modify the tool's behavior by providing flags as mentioned in the usage section. Here are some configurable options:

- `interval`: The time interval (in seconds) between each scraping process.  
- `token`: Your Discord Bot token.  
- `channel-id`: The ID of the Discord channel where notifications will be posted.  

## 💪 Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## 📜  License
This project is licensed under the MIT License.

## 🙏 Acknowledgments
- This tool utilizes the [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) library for web scraping.
- Special thanks to [The Hacker News](https://thehackernews.com/) for providing valuable cybersecurity news.

*** 


