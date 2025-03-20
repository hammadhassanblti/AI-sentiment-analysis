# AI Sentiment Analyzer

![image](https://github.com/user-attachments/assets/b6ad7b95-c679-4b37-8a4e-a7841e650c98)
![image](https://github.com/user-attachments/assets/5034641a-1c1c-40d3-a808-a8b37fb58c86)
![image](https://github.com/user-attachments/assets/beab219d-be11-454d-9647-b0bba4839b0e)



## 📱 Overview

AI Sentiment Analyzer is a web application that extracts and analyzes product information and user reviews from WhatMobile.pk. The tool provides comprehensive sentiment analysis of reviews, helping users make informed decisions about mobile phones based on user experiences.

## ✨ Features

- **Web Scraping**: Extracts product details and user reviews from WhatMobile.pk
- **Data Extraction**: Collects product prices, titles, descriptions, and user comments/reviews
- **Sentiment Analysis**: Analyzes user reviews to determine sentiment (positive, negative, neutral)
- **User-Friendly Interface**: Simple two-step process for analyzing any WhatMobile.pk URL
- **Contextual Analysis**: Allows users to enter additional text for analysis in the context of scraped data

## 🚀 How It Works

1. Enter a WhatMobile.pk URL in the first input field
2. Click "Analyze" to scrape the product details
3. (Optional) Enter additional text in the second field for contextual analysis
4. Click "Analyze Sentiment" to process and view results

## 💻 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python
- **Web Scraping**: BeautifulSoup/Scrapy
- **NLP/Sentiment Analysis**: Transformer-based models
- **Development Environment**: Cursor Editor

## 🛠️ Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-sentiment-analyzer.git
   cd ai-sentiment-analyzer
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## 📋 Project Structure

```
ai-sentiment-analyzer/
├── app.py                 # Main application file
├── scraper.py             # Web scraping functionality
├── sentiment_analyzer.py  # Sentiment analysis logic
├── static/                # Static assets (CSS, JS, images)
│   ├── css/               # Stylesheets
│   └── js/                # JavaScript files
├── templates/             # HTML templates
├── requirements.txt       # Project dependencies
└── README.md              # Project documentation
```

## 🧠 Development Process

The development of this project involved several key steps:

1. **Scraping Phase**: Developed code to extract data from WhatMobile.pk
2. **Data Processing**: Organized the scraped data into structured format
3. **UI Design**: Created a clean, intuitive interface using Cursor editor
4. **Integration**: Connected the scraping module with the sentiment analysis engine
5. **Testing & Refinement**: Tested with various mobile phone listings and refined the analysis

## 📈 Future Improvements

- Add support for more e-commerce and review websites
- Implement more detailed sentiment analysis with aspect-based opinions
- Create visualization dashboards for sentiment trends
- Add user accounts to save analysis history
- Develop browser extension for quick analysis

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributions

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📞 Contact

Creator - M.Hammad Hassan  - hammadblti302@gmail.com

Project Link: https://github.com/hammadhassanblti/AI-sentiment-analysis/tree/main
